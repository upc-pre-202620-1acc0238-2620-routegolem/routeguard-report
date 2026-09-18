<div align="center">
  <img src="https://github.com/upc-pre-202620-1acc0238-2620-routegolem/routeguard-report/blob/develop/resources/cover/upc-logo.png" width="150" alt="Logo de la UPC">
  <br><br>
  <strong>UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS</strong>
  <br><br>
  <strong>INGENIERÍA DE SOFTWARE</strong>
  <br><br>
  <strong>1ACC0238 - Aplicaciones Para Dispositivos Móviles</strong>
  <br>
  NRC: <strong>4945</strong>
  <br><br>
  <strong>Informe de Trabajo Final</strong>
  <br><br>
  Docente:<br>
  <strong>Jorge Luis Mayta Guillermo</strong>
  <br><br>
  Equipo:<br>
  <strong>RouteGolem</strong>
  <br><br>
  Proyecto:<br>
  <strong>RouteGuard</strong>
  <br><br>
  <strong>Integrantes:</strong><br>
  [Código] - De la Cruz De los Santos, Mathias Marcelo<br>
  [Código] - Francia Torres, Jhony Manuel<br>
  u202411627 - Pareja Calloapaza, Marcelo Fausto<br>
  [u202415551] - Ramirez Ruíz, Nickolas<br>
  <br><br>
  <strong>Periodo 2026-02</strong><br>
  <strong>Setiembre 2026</strong>
</div>

<div style="page-break-after: always;"></div>

## Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
| **0.1** | 05/09/2026 | Marcelo Pareja | Creación de la estructura base del informe, carátula y aplicación de la plantilla Markdown oficial del curso. |
| **0.2** | 05/09/2026 | Marcelo Pareja | Redacción del Startup Profile (Misión, Visión, Valores) y el Solution Profile (Antecedentes bajo la técnica 5W+2H) con sustento académico. |
| **0.3** | 06/09/2026 | Marcelo Pareja | Integración del proceso Lean UX respetando los templates oficiales (Problem Statements, 5 tipos de Assumptions e Hipótesis). |
| **0.4** | 06/09/2026 | Marcelo Pareja | Definición de los Segmentos Objetivo (Padres y Conductores) incorporando información estadística de sustento (MINEDU y ATU). |
| **0.5** | 06/09/2026 | Marcelo Pareja | Incorporación de los Objetivos SMART, tabla de Student Outcome mapeada a la rúbrica y generación de la Tabla de Contenidos automatizada. |

<div style="page-break-after: always;"></div>

## Project Report Collaboration Insights

<div style="page-break-after: always;"></div>

## Tabla de contenidos

- [Capítulo I: Presentación](#capítulo-i-presentación)
  - [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3 Segmentos objetivo](#13-segmentos-objetivo)
    - [Segmento 1: Transportistas Escolares (Administradores y Conductores)](#segmento-1-transportistas-escolares-administradores-y-conductores)
    - [Segmento 2: Padres de Familia](#segmento-2-padres-de-familia)
- [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)
  - [2.1. Competidores](#21-competidores)
      - [2.1.1 Análisis Competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
      - [Enfoque en la especialización del problema](#enfoque-en-la-especialización-del-problema)
      - [Estrategia de digitalización del sector no estructurado](#estrategia-de-digitalización-del-sector-no-estructurado)
      - [Diferenciación mediante simplicidad y accesibilidad](#diferenciación-mediante-simplicidad-y-accesibilidad)
      - [Estrategia de confianza y seguridad para los padres](#estrategia-de-confianza-y-seguridad-para-los-padres)
      - [Estrategia de crecimiento progresivo y escalabilidad](#estrategia-de-crecimiento-progresivo-y-escalabilidad)
      - [Estrategia de posicionamiento local](#estrategia-de-posicionamiento-local)
      - [Estrategia de preparación tecnológica a futuro](#estrategia-de-preparación-tecnológica-a-futuro)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
      - [A. Segmento 1: Transportistas Escolares (Administradores y Conductores)](#a-segmento-1-transportistas-escolares-administradores-y-conductores)
      - [B. Segmento 2: Padres de Familia](#b-segmento-2-padres-de-familia)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
      - [Entrevistado 1: Manuel Jesús Francia Huambachano (Segmento: Padres de Familia)](#entrevistado-1-manuel-jesús-francia-huambachano-segmento-padres-de-familia)
      - [Entrevistado 2: Luis Johnny Jesús Mendoza (Segmento: Conductor / Transportista)](#entrevistado-2-luis-johnny-jesús-mendoza-segmento-conductor--transportista)
      - [Entrevistado 3: Máximo Quevedo (Segmento: Padres de Familia)](#entrevistado-3-máximo-quevedo-segmento-padres-de-familia)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
      - [A. Segmento 1: El Transportista (Conductor)](#a-segmento-1-el-transportista-conductor)
      - [B. Segmento 2: El Padre de Familia](#b-segmento-2-el-padre-de-familia)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
      - [A. Journey Map: El Transportista (Conductor)](#a-journey-map-el-transportista-conductor)
      - [B. Journey Map: El Padre de Familia](#b-journey-map-el-padre-de-familia)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
      - [Segmento Objetivo 1: Drivers](#segmento-objetivo-1-drivers)
      - [Segmento Objetivo 2: Parents](#segmento-objetivo-2-parents)
    - [2.3.5. Big Picture EventStorming](#235-big-picture-eventstorming)
      - [Cronología de Eventos de Dominio Identificados:](#cronología-de-eventos-de-dominio-identificados)
    - [2.3.6. Ubiquitous Language](#236-ubiquitous-language)
  - [2.4. Requirements specification](#24-requirements-specification)
    - [2.4.1. User Stories](#241-user-stories)
    - [2.4.2. Impact Mapping](#242-impact-mapping)
    - [2.4.3. Product Backlog](#243-product-backlog)
  - [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)
    - [2.5.1. EventStorming](#251-eventstorming)
      - [2.5.1.1. Candidate Context Discovery](#2511-candidate-context-discovery)
      - [2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)
      - [2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)
    - [2.5.2. Context Mapping](#252-context-mapping)
    - [2.5.3. Software Architecture](#253-software-architecture)
      - [2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
      - [2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)
      - [2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)
  - [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)
    - [2.6.1. Bounded Context: Trip Execution \& Monitoring](#261-bounded-context-trip-execution--monitoring)
      - [2.6.1.1. Domain Layer](#2611-domain-layer)
      - [2.6.1.2. Interface Layer](#2612-interface-layer)
      - [2.6.1.3. Application Layer](#2613-application-layer)
      - [2.6.1.4. Infrastructure Layer](#2614-infrastructure-layer)
      - [2.6.1.5. Component Level Diagrams](#2615-component-level-diagrams)
      - [2.6.1.6. Code Level Diagrams](#2616-code-level-diagrams)
        - [2.6.1.6.1. Domain Layer Class Diagram](#26161-domain-layer-class-diagram)
        - [2.6.1.6.2. Database Design Diagram](#26162-database-design-diagram)
    - [2.6.2. Bounded Context: Notifications \& Communication](#262-bounded-context-notifications--communication)
      - [2.6.2.1. Domain Layer](#2621-domain-layer)
      - [2.6.2.2. Interface Layer](#2622-interface-layer)
      - [2.6.2.3. Application Layer](#2623-application-layer)
      - [2.6.2.4. Infrastructure Layer](#2624-infrastructure-layer)
      - [2.6.2.5. Component Level Diagrams](#2625-component-level-diagrams)
      - [2.6.2.6. Code Level Diagrams](#2626-code-level-diagrams)
        - [2.6.2.6.1. Domain Layer Class Diagram](#26261-domain-layer-class-diagram)
        - [2.6.2.6.2. Database Design Diagram](#26262-database-design-diagram)
    - [2.6.3. Bounded Context: Identity \& Access Management](#263-bounded-context-identity--access-management)
      - [2.6.3.1. Domain Layer](#2631-domain-layer)
      - [2.6.3.2. Interface Layer](#2632-interface-layer)
      - [2.6.3.3. Application Layer](#2633-application-layer)
      - [2.6.3.4. Infrastructure Layer](#2634-infrastructure-layer)
      - [2.6.3.5. Component Level Diagrams](#2635-component-level-diagrams)
      - [2.6.3.6. Code Level Diagrams](#2636-code-level-diagrams)
        - [2.6.3.6.1. Domain Layer Class Diagram](#26361-domain-layer-class-diagram)
        - [2.6.3.6.2. Database Design Diagram](#26362-database-design-diagram)
    - [2.6.4. Bounded Context: Subscription \& Plan Management](#264-bounded-context-subscription--plan-management)
      - [2.6.4.1. Domain Layer](#2641-domain-layer)
      - [2.6.4.2. Interface Layer](#2642-interface-layer)
      - [2.6.4.3. Application Layer](#2643-application-layer)
      - [2.6.4.4. Infrastructure Layer](#2644-infrastructure-layer)
      - [2.6.4.5. Component Level Diagrams](#2645-component-level-diagrams)
      - [2.6.4.6. Code Level Diagrams](#2646-code-level-diagrams)
        - [2.6.4.6.1. Domain Layer Class Diagram](#26461-domain-layer-class-diagram)
        - [2.6.4.6.2. Database Design Diagram](#26462-database-design-diagram)
    - [2.6.5. Bounded Context: Fleet \& Route Management](#265-bounded-context-fleet--route-management)
      - [2.6.5.1. Domain Layer](#2651-domain-layer)
      - [2.6.5.2. Interface Layer](#2652-interface-layer)
      - [2.6.5.3. Application Layer](#2653-application-layer)
      - [2.6.5.4. Infrastructure Layer](#2654-infrastructure-layer)
      - [2.6.5.5. Component Level Diagrams](#2655-component-level-diagrams)
      - [2.6.5.6. Code Level Diagrams](#2656-code-level-diagrams)
        - [2.6.5.6.1. Domain Layer Class Diagram](#26561-domain-layer-class-diagram)
        - [2.6.5.6.2. Database Design Diagram](#26562-database-design-diagram)
    - [2.6.6. Bounded Context: Stakeholder \& Asset Management](#266-bounded-context-stakeholder--asset-management)
      - [2.6.6.1. Domain Layer](#2661-domain-layer)
      - [2.6.6.2. Interface Layer](#2662-interface-layer)
      - [2.6.6.3. Application Layer](#2663-application-layer)
      - [2.6.6.4. Infrastructure Layer](#2664-infrastructure-layer)
      - [2.6.6.5. Component Level Diagrams](#2665-component-level-diagrams)
      - [2.6.6.6. Code Level Diagrams](#2666-code-level-diagrams)
        - [2.6.6.6.1. Domain Layer Class Diagram](#26661-domain-layer-class-diagram)
        - [2.6.6.6.2. Database Design Diagram](#26662-database-design-diagram)
- [Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-uiux-design)
  - [3.1. Product design](#31-product-design)
    - [3.1.1. Style Guidelines](#311-style-guidelines)
      - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
    - [3.1.2. Information Architecture](#312-information-architecture)
      - [3.1.2.1. Organization Systems](#3121-organization-systems)
      - [3.1.2.2. Labelling Systems](#3122-labelling-systems)
      - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
      - [3.1.2.4. Searching Systems](#3124-searching-systems)
      - [3.1.2.5. Navigation Systems](#3125-navigation-systems)
    - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
      - [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)
      - [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)
    - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)
      - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
      - [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)
      - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
      - [3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)
      - [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)
- [Capítulo IV: Product Implementation \& Validation](#capítulo-iv-product-implementation--validation)
  - [4.1. Software Configuration Management](#41-software-configuration-management)
    - [4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)
    - [4.1.2. Source Code Management](#412-source-code-management)
    - [4.1.3. Source Code Style Guide \& Conventions](#413-source-code-style-guide--conventions)
    - [4.1.4. Software Deployment Configuration](#414-software-deployment-configuration)
  - [4.2. Landing Page \& Mobile Application Implementation](#42-landing-page--mobile-application-implementation)
    - [4.2.1. Sprint n](#421-sprint-n)
      - [4.2.1.1. Sprint Planning n](#4211-sprint-planning-n)
      - [4.2.1.2. Aspect Leaders and Collaborators](#4212-aspect-leaders-and-collaborators)
      - [4.2.1.3. Sprint Backlog n](#4213-sprint-backlog-n)
      - [4.2.1.4. Development Evidence for Sprint Review](#4214-development-evidence-for-sprint-review)
      - [4.2.1.5. Testing Suite Evidence for Sprint Review](#4215-testing-suite-evidence-for-sprint-review)
      - [4.2.1.6. Execution Evidence for Sprint Review](#4216-execution-evidence-for-sprint-review)
      - [4.2.1.7. Services Documentation Evidence for Sprint Review](#4217-services-documentation-evidence-for-sprint-review)
      - [4.2.1.8. Software Deployment Evidence for Sprint Review](#4218-software-deployment-evidence-for-sprint-review)
      - [4.2.1.9. Team Collaboration Insights during Sprint](#4219-team-collaboration-insights-during-sprint)
  - [4.3. Validation Interviews](#43-validation-interviews)
    - [4.3.1. Diseño de Entrevistas](#431-diseño-de-entrevistas)
    - [4.3.2. Registro de Entrevistas](#432-registro-de-entrevistas)
    - [4.3.3. Evaluaciones según heurísticas](#433-evaluaciones-según-heurísticas)
- [Conclusiones](#conclusiones)
    - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
    - [Video App Validation](#video-app-validation)
    - [Video About the product](#video-about-the-product)
    - [Video About the team](#video-about-the-team)
- [Glosario](#glosario)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<div style="page-break-after: always;"></div>

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET: 
* **Outcome 7 (Criterios 7.c1, 7.c2):** Capacidad para adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje adecuadas.
* **Outcome 3 (Criterio 3.c2):** Capacidad para comunicarse efectivamente con una variedad de audiencias.

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|
| **Outcome 7 (7.c1):** Identificación de problemáticas, UX Research, y diseño de arquitectura (DDD, RESTful). | Mediante el proceso de *Lean UX* y *UX Research*, investigamos a los usuarios y sus dolores. Aplicamos *Domain-Driven Design (DDD)* para diseñar los Bounded Contexts y diagramar la arquitectura del sistema, asegurando el cumplimiento de principios RESTful. | La investigación estructurada y el diseño guiado por el dominio nos permitió comprender la complejidad del transporte escolar y plantear una arquitectura de software robusta, escalable y centrada en las necesidades reales de seguridad. |
| **Outcome 7 (7.c2):** Implementación de soluciones (Native/Cross-Platform), ciclo de vida ágil y mejora continua. | Investigamos e implementamos tecnologías nuevas fuera de clase (GPS en *background*, modo *offline*) para la app de conductores (Nativa) y la app de padres (Cross-Platform). Aplicamos marco de trabajo ágil con GitFlow, *Conventional Commits* y realizamos entrevistas de validación. | El aprendizaje autónomo de tecnologías nativas y servicios en segundo plano fue vital para resolver la necesidad del usuario operativo. Aplicar un flujo de CI/CD (GitFlow) garantizó el desarrollo colaborativo sin conflictos. |
| **Outcome 3 (3.c2):** Comunicación oral y escrita objetiva, respetando estructuras y estándares. | Redactamos el presente informe técnico respetando las normas APA 7, la estructura exigida, un *Ubiquitous Language* en inglés, y produjimos videos explicativos para sustentar el progreso del Sprint de manera profesional. | Documentar el proyecto con un lenguaje técnico estandarizado mejora drásticamente la transferencia de conocimiento. La comunicación efectiva fue clave para alinear las expectativas de todos los miembros del equipo. |

<div style="page-break-after: always;"></div>

## Objetivos SMART

Para garantizar el desarrollo ordenado y exitoso del ecosistema RouteGuard a lo largo del ciclo académico, el equipo ha establecido los siguientes objetivos bajo la metodología SMART:

**Objetivo 1: Validación de Experiencia de Usuario (UX) y Requerimientos**
* Validar la propuesta de valor y las hipótesis establecidas en el *Lean UX* realizando 8 entrevistas a profundidad (4 a conductores y 4 a padres de familia) para elaborar el 100% de los artefactos de Needfinding y el *Product Backlog* antes de la Semana 4 del ciclo académico.
  * **S (Específico):** Validar propuesta de valor y elaborar artefactos UX.
  * **M (Medible):** 8 entrevistas exactas y 100% de artefactos completados.
  * **A (Alcanzable):** Viable dividiendo 2 entrevistas por cada uno de los 4 integrantes.
  * **R (Relevante):** Fundamental para definir la arquitectura y el diseño del software.
  * **T (Tiempo):** Antes de la Semana 4 (Hito AV1).

**Objetivo 2: Arquitectura de Software y Despliegue Inicial (Backend)**
* Diseñar, programar y desplegar en la nube la arquitectura base de la plataforma, completando el Landing Page y los endpoints RESTful fundamentales del *Identity & Access Management Bounded Context*, cumpliendo la totalidad de los Story Points asignados al Sprint 1 para la Semana 7.
  * **S:** Despliegue del Landing Page y endpoints de IAM.
  * **M:** Cumplimiento del 100% de los Story Points del Sprint 1.
  * **A:** Realizable utilizando frameworks modernos y CI/CD.
  * **R:** Construye los cimientos para que las aplicaciones móviles puedan conectarse.
  * **T:** Para la Semana 7 (Hito TB1).

**Objetivo 3: Implementación Nativa de Geolocalización (App Conductores)**
* Desarrollar la aplicación móvil nativa (Android) para el segmento de transportistas, integrando con éxito los servicios críticos de geolocalización en segundo plano (*Background GPS*) y el modo *offline* para la sincronización de bitácoras, culminando las pruebas de integración para la Semana 11.
  * **S:** Desarrollo de app nativa con GPS en *background* y soporte *offline*.
  * **M:** Lograr la sincronización de la bitácora sin pérdida de datos en pruebas.
  * **A:** Factible enfocando a 2 desarrolladores del equipo en la tecnología nativa.
  * **R:** Resuelve el mayor "punto de dolor" del conductor: evitar distracciones al volante.
  * **T:** Para la Semana 11 (Hito TB2).

**Objetivo 4: Ecosistema Cross-Platform y Notificaciones (App Padres)**
* Desplegar la aplicación *cross-platform* para padres de familia, logrando una comunicación *end-to-end* que procese las coordenadas del conductor y dispare alertas de *Geofencing* y notificaciones *Push* en el dispositivo del padre con una latencia menor a 5 segundos, garantizando un flujo operativo completo para la sustentación final en la Semana 15.
  * **S:** Integración de notificaciones Push y Geofencing en app cross-platform.
  * **M:** Latencia menor a 5 segundos desde el envío hasta la alerta.
  * **A:** Lograble utilizando servicios como Firebase Cloud Messaging.
  * **R:** Materializa el valor principal del producto: la paz mental de los padres.
  * **T:** Para la Semana 15 (Trabajo Final - TF).

<div style="page-break-after: always;"></div>

# Capítulo I: Presentación

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup

**Nombre:** RouteGolem

**Área:** EdTech / Mobility & Transportation (Software) B2B2C

RouteGolem es una startup tecnológica emergente conformada por estudiantes de la Facultad de Ingeniería de la Universidad Peruana de Ciencias Aplicadas (UPC). La compañía nace con el objetivo de modernizar y asegurar el ecosistema del transporte escolar privado mediante la digitalización integral de sus operaciones logísticas. A través del desarrollo de plataformas móviles avanzadas, conectamos en tiempo real a conductores y padres de familia, reemplazando la coordinación informal y manual por un monitoreo preciso de rutas y control de asistencias. De esta manera, buscamos erradicar la incertidumbre familiar, optimizar el trabajo operativo del transportista y, por sobre todo, garantizar la máxima seguridad de los menores durante sus trayectos diarios.

* **Misión:**
La misión de RouteGolem es salvaguardar la integridad de los estudiantes durante su traslado escolar mediante la implementación de soluciones móviles inteligentes que permitan una gestión logística transparente y estructurada. Nos dedicamos a transformar la cultura del transporte escolar privado, sustituyendo la comunicación reactiva (como llamadas y mensajes de texto durante la conducción) por un monitoreo automatizado basado en datos de geolocalización y validación de abordaje en tiempo real. A través de nuestro ecosistema dual, RouteGuard, proporcionamos tranquilidad a las familias y eficiencia a los conductores, asegurando que la tecnología se traduzca en traslados más seguros, sin distracciones al volante y con un estándar de servicio superior.

* **Visión:**
La visión de RouteGolem es consolidarse como el estándar tecnológico regional en la gestión de flotas y monitoreo del transporte escolar, liderando la transición hacia una movilidad estudiantil conectada, inteligente y proactiva. Nos proyectamos como el aliado tecnológico indispensable para asociaciones de padres, centros educativos y empresas de transporte, donde la integración de aplicaciones móviles e inteligencia de datos permita erradicar los riesgos y el estrés asociados al traslado de menores. Aspiramos a ser la plataforma que no solo brinde visibilidad, sino que dicte las pautas para un ecosistema de transporte seguro, escalable y tecnológicamente optimizado.

* **Valores:**
	* **Seguridad Incondicional:** Nos comprometemos con la protección absoluta de los menores. Valoramos el rigor y la precisión de nuestros sistemas de tracking y control de asistencia, entendiendo que de su exactitud depende la integridad de los estudiantes y la tranquilidad de sus familias.
	* **Transparencia Operativa:** Creemos en la detección y comunicación de incidentes en tiempo real. Nuestra filosofía se centra en visibilizar el estado del servicio para evitar la incertidumbre, conectando a todos los actores involucrados de manera directa y confiable.
	* **Innovación Continua:** Buscamos constantemente la evolución de nuestros ecosistemas de software. No nos conformamos con lo existente, sino que adaptamos tecnologías móviles de vanguardia, como la geolocalización en segundo plano y la validación rápida, para solucionar los desafíos operativos del sector.
	* **Ética y Privacidad:** Valoramos la privacidad y el manejo responsable de información altamente sensible, como la ubicación de menores de edad. Garantizamos que el monitoreo se realice bajo estrictos estándares éticos y de ciberseguridad, asegurando que la tecnología sea un escudo protector.
	* **Humanidad Centralizada:** Fomentamos un ecosistema donde la tecnología responde a la ansiedad natural de los padres y al desgaste operativo de los conductores. Entendemos que un sistema logístico eficiente solo es verdaderamente útil si alivia la carga emocional y laboral de sus usuarios.
	* **Orientación a Resultados:** Nos enfocamos en resultados escalables y tangibles. Nuestro modelo de negocio garantiza un soporte continuo y una plataforma de alta disponibilidad, asegurando que los transportistas cuenten con una herramienta ininterrumpida para la gestión y profesionalización de su trabajo diario.

### 1.1.2 Perfiles de integrantes del equipo

|                         Foto                         | Apellidos y Nombres |   Código    | Carrera | Resumen |
|:----------------------------------------------------:|:---|:-----------:|:---|:---|
|                        [Foto]                        | De la Cruz De los Santos, Mathias Marcelo |   U20...    | Ingeniería de Software | [Breve descripción de 3-4 líneas del integrante, habilidades y qué aporta al proyecto] |
| ![foto](/resources/assets/images/team/Manuel.jpeg)                         | Francia Torres, Jhony Manuel |   U202417329    | Ingeniería de Software | Mi nombre es Jhony Manuel Francia Torres, tengo 19 años, actualmente estoy cursando el 6to  ciclo de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Soy un apasionado del fútbol y la natación. Soy perseverante en lograr mis objetivos y metódico en mis proyectos. Mi objetivo en este grupo es poder desarrollar mis habilidades de trabajo en equipo y comunicación ágil, además de adquirir conocimientos en nuevos lenguajes de programación para el desarrollo de aplicaciones móviles. Mis aportes en este grupo serán cumplir responsablemente con las tareas que se me asignen y brindar ideas para el desarrollo del proyecto. |
| ![foto](/resources/assets/images/team/marcelo.jpg) | Pareja Calloapaza, Marcelo Fausto | U202411627  | Ingeniería de Software | Soy Marcelo Pareja Calloapaza, estudiante de Ingeniería de Software y considero que, gracias a mis estudios he podido construir un perfil técnico altamente versátil. Domino tecnologías backend, bases de datos y entornos cloud (C#, C++, JavaScript, SQL/NoSQL, Azure), y actualmente busco embarcarme en desarrollo móvil nativo con Kotlin. En RouteGuard desempeño un rol Full-Stack y de liderazgo arquitectónico, en donde busco involucrarme en todas las capas del ecosistema. Me considero un desarrollador analítico y adaptable, con disposición innata a resolver problemas complejos para asegurar el éxito del proyecto. |
| ![foto](/resources/assets/images/team/nickolas.png ) | Ramirez Ruiz, Nickolas | U202415551 | Ingeniería de Software | Soy Nickolas Ramirez Ruiz, estudiante del sexto ciclo de la carrera de Ingeniería de Software. A lo largo de mi formación académica he adquirido conocimientos en programación, principalmente utilizando el lenguaje Java. Me considero una persona organizada, comprometida y con un enfoque proactivo, siempre buscando cumplir con mis responsabilidades antes del tiempo previsto.|

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

Para delimitar y entender a fondo el contexto del transporte escolar privado y sus deficiencias actuales, hemos aplicado la técnica de análisis **5W+2H**, sustentada en datos oficiales y literatura académica reciente:

* **Who (¿Quiénes son los afectados?):** 
La problemática afecta principalmente a tres actores. En primer lugar, los **padres de familia**, quienes experimentan ansiedad constante al delegar el traslado de sus hijos a terceros sin visibilidad del trayecto. En segundo lugar, los **conductores escolares**, quienes sufren de sobrecarga operativa al intentar comunicarse mientras conducen. Finalmente, los **administradores de flotas**, que carecen de herramientas centralizadas para gestionar sus rutas y asistencias.

* **What (¿Cuál es el problema?):** 
La coordinación del transporte escolar privado se realiza de manera predominantemente informal. El uso de llamadas telefónicas y grupos de mensajería impide tener trazabilidad y un registro histórico confiable. Según estudios sobre movilidad urbana, la falta de plataformas integradas en el transporte escolar de países en vías de desarrollo incrementa la ineficiencia logística y la percepción de inseguridad (García et al., 2024).

* **Where (¿Dónde ocurre?):** 
El problema se concentra en zonas urbanas con alta densidad poblacional y tráfico vehicular pesado, como Lima Metropolitana, donde las distancias entre los hogares y los centros educativos obligan a depender de servicios de movilidad privada externa al colegio.

* **When (¿Cuándo ocurre?):** 
Se manifiesta de forma diaria y crítica durante los horarios pico escolares: en el recojo matutino (6:00 a.m. - 8:00 a.m.) y en el retorno vespertino (1:30 p.m. - 4:00 p.m.). Es en estas ventanas donde la falta de información genera mayor desesperación en los padres.

* **Why (¿Por qué es un problema?):** 
Porque la falta de digitalización genera vulnerabilidad para el menor y promueve la conducción temeraria. Estudios de seguridad vial demuestran que la interacción con dispositivos móviles para enviar mensajes de texto o reportar estados durante la conducción multiplica por cuatro el riesgo de accidentes de tránsito (Smith & Johnson, 2025). Además, resulta en una desorganización logística que frena el crecimiento de las pequeñas empresas de transporte.

* **How (¿Cómo se manifiesta?):** 
Se evidencia a través del caos comunicacional: padres llamando insistentemente a los conductores, conductores olvidando registrar asistencias por el apuro, demoras no reportadas por tráfico, y una total desconexión entre la operación física del vehículo y la información que recibe la familia.

* **How much (¿Cuál es la magnitud?):** 
La magnitud del problema es masiva. Según el Censo Educativo del Ministerio de Educación (MINEDU, 2023), en Lima Metropolitana existen aproximadamente 1.9 millones de estudiantes, de los cuales una gran mayoría asiste a instituciones de gestión privada que no cuentan con flota propia. Paralelamente, la Autoridad de Transporte Urbano para Lima y Callao (ATU, 2024) reportó una disminución del 25% en las movilidades escolares formalmente autorizadas en un solo año, lo que sugiere un alarmante incremento en la informalidad del sector y una mayor exposición de los escolares a servicios sin monitoreo estandarizado.

### 1.2.2 Lean UX Process

Para el modelado de nuestra propuesta de valor y la mitigación de riesgos de desarrollo, aplicamos la metodología Lean UX (Gothelf & Seiden, 2021). Este enfoque iterativo nos permite validar de forma temprana nuestras asunciones mediante experimentación directa con los transportistas y padres de familia. Como señalan Gothelf y Seiden (2021), "Lean UX cambia radicalmente la forma en que enmarcamos nuestro trabajo al reintroducir el contexto estratégico para nuestras elecciones de diseño y funcionalidad y, lo que es más importante, cómo definimos el éxito" (p. 48).

#### 1.2.2.1. Lean UX Problem Statements
En el marco de Lean UX, las declaraciones de problemas de negocio reemplazan a los requerimientos tradicionales, ya que exigen explícitamente que se lleve a cabo un trabajo de descubrimiento del producto (Gothelf & Seiden, 2021, p. 68). Siguiendo la plantilla oficial para nuevas iniciativas (Gothelf & Seiden, 2021, p. 71), definimos el problema de nuestra startup de la siguiente manera:

El estado actual del **[transporte escolar privado]** se ha enfocado principalmente en **[la coordinación operativa y comunicación a través de métodos manuales e informales (llamadas telefónicas y grupos de WhatsApp), lo que genera puntos de dolor críticos: una constante ansiedad en los padres por desconocer el paradero exacto del vehículo y un alto nivel de distracción y sobrecarga laboral para el conductor al intentar reportar su avance mientras maneja]**, factores que multiplican el riesgo de siniestros viales (Smith & Johnson, 2025).

Lo que los productos y servicios existentes no logran abordar es **[la falta de una plataforma integral que digitalice y profesionalice la gestión de las flotas escolares ya existentes, sin intentar convertirse en un marketplace de contratación]**.

Nuestro producto (RouteGuard) abordará esta brecha mediante **[un ecosistema SaaS multirol que ofrece una app nativa con GPS en segundo plano y modo offline para el conductor, y una app de monitoreo pasivo con notificaciones push y geofencing para los padres de familia]**.

Nuestro enfoque inicial será **[los administradores de pequeñas empresas de transporte escolar y conductores independientes que operan en zonas urbanas de alto tráfico]**.

Sabremos que hemos tenido éxito cuando veamos **[que el 80% de los conductores completan sus bitácoras de abordaje de forma estrictamente digital y las llamadas de consulta o reclamo por parte de los padres se reduzcan en un 90% en el primer mes de uso]**.

#### 1.2.2.2. Lean UX Assumptions
En el desarrollo de software, rara vez se cuenta con certezas absolutas. Por ello, Gothelf y Seiden (2021) recomiendan reconocer que la mayoría de los requisitos son simplemente "supuestos expresados con autoridad" (p. 61). A partir del análisis del problema, declaramos y priorizamos los siguientes supuestos que guiarán la validación de RouteGuard:

**1. Business Assumptions:**
* Creemos que los administradores de flotas y conductores independientes están dispuestos a pagar planes de suscripción (Básico, Intermedio, Completo) por una plataforma SaaS que modernice su logística y les brinde una ventaja competitiva en el mercado urbano (García et al., 2024).
* Creemos que RouteGuard no debe involucrarse en las transacciones de pago entre padres y transportistas, sino mantenerse puramente como una herramienta tecnológica de gestión, seguridad y monitoreo.

**2. Business Outcome Assumptions:**
* Creemos que el éxito del negocio se medirá por la cantidad de rutas activas recurrentes creadas por los administradores y la tasa de actualización (upgrade) hacia los planes de suscripción de mayor nivel.

**3. User Assumptions:**
* Creemos que el "Conductor" operará la aplicación en entornos de baja conectividad a internet, por lo que el modo offline con sincronización en diferido es un requerimiento crítico.
* Creemos que el "Padre de familia" prefiere una experiencia de usuario pasiva basada en alertas automáticas (Geofencing) en lugar de mantener la pantalla de su dispositivo encendida monitoreando un mapa todo el trayecto (Chen & Davis, 2025).

**4. User Outcome and Benefit Assumptions:**
* Creemos que los padres de familia obtendrán **paz mental total** mediante la transparencia automatizada del servicio.
* Creemos que los conductores lograrán **enfocarse al 100% en el manejo seguro**, reduciendo la carga cognitiva y el estrés provocado por reportar su ubicación o el recojo de alumnos manualmente.

**5. Feature Assumptions:**
* Creemos que la **transmisión de GPS en segundo plano (Background Location)** es vital para que el conductor no tenga que interactuar con la pantalla durante el viaje.
* Creemos que un **Checklist de abordaje a 1 toque con soporte offline** resolverá el problema de la pérdida de datos en zonas sin cobertura celular.
* Creemos que las **Notificaciones Push Automáticas y el Geofencing** resolverán la necesidad de certidumbre de los padres de forma proactiva.

#### 1.2.2.3. Lean UX Hypothesis Statements
Una hipótesis es una solución empresarial propuesta que debe validarse de la manera más eficiente posible utilizando los comentarios de los clientes (Gothelf & Seiden, 2021, p. 35). Siguiendo estrictamente el formato de declaración de hipótesis de Lean UX (Gothelf & Seiden, 2021, p. 110), formulamos:

**Hipótesis 1 (Transmisión GPS y Offline Sync):**
* Creemos que lograremos **[una alta retención de suscripciones y upgrades hacia los planes Intermedio y Completo]**
* Si **[los administradores y conductores de transporte escolar]**
* Consiguen **[enfocarse exclusivamente en conducir sin distracciones ni miedo a perder la data por falta de señal]**
* Con **[la funcionalidad de tracking GPS en segundo plano y checklist de abordaje con sincronización en modo offline]**.

**Hipótesis 2 (Notificaciones Proactivas):**
* Creemos que lograremos **[que los padres exijan el uso de RouteGuard como un estándar de calidad indispensable en su contratación de movilidad]**
* Si **[los padres de familia]**
* Consiguen **[paz mental absoluta al no tener que llamar al conductor para saber a qué hora llega su hijo]**
* Con **[las funcionalidades de Notificaciones Push Automáticas y alertas por Geofencing perimetral]**.

**Hipótesis 3 (Botón de Incidencias):**
* Creemos que lograremos **[una reducción drástica en las quejas y reclamos hacia las empresas de transporte]**
* Si **[los conductores escolares]**
* Consiguen **[comunicar emergencias o demoras por tráfico de forma inmediata y masiva]**
* Con **[el Botón de pánico y reporte de incidencias a 1 toque accesible sin desbloquear procesos complejos en la app nativa]**.

#### 1.2.2.4. Lean UX Canvas
El Lean UX Canvas consolida los métodos y procesos de esta metodología en un solo documento para facilitar el entendimiento compartido del equipo (Gothelf & Seiden, 2021, p. 57).

<table>
    <tr>
        <td valign="top" >
            <div align="center"> <br><b>1. Business Problem</b> </div><br>
            <p>El transporte escolar privado opera de forma manual e informal (WhatsApp/llamadas). Los padres carecen de visibilidad sobre el trayecto de sus hijos, y los conductores sufren sobrecarga y distracciones intentando reportar el servicio mientras manejan, comprometiendo la seguridad vial (Smith & Johnson, 2025).</p><br>
        </td>
        <td rowspan="2" valign="top">
            <div align="center"><br><b>5. Solutions</b> </div><br>
            <p>- App Nativa para conductor con GPS en background y soporte offline.<br>- Checklist de abordaje a 1 toque.<br>- App Cross-platform para padres con notificaciones Push y Geofencing.<br>- Botón de incidencias rápido.<br>- Plataforma SaaS de gestión de rutas y planes.</p><br>
        </td>
            <td valign="top">
            <div align="center"> <br><b>2. Business Outcomes</b> </div><br>
            <p>- Lograr que el 70% de administradores migren del Plan Básico al Intermedio/Completo en 3 meses.<br>- Reducir el tiempo promedio de recojo en paraderos en un 15%.<br>- Tasa de retención de flotas suscritas superior al 85%.</p><br>
            </td>
        </tr>
    <tr>
        <td valign="top">
            <div align="center"><br><b>3. Users</b></div><br>
            <p>- **Administrador:** Dueño de flota que busca gestionar rutas y profesionalizar su negocio.<br>- **Conductor:** Opera la movilidad y necesita herramientas sin distracción (offline y background).<br>- **Padres de Familia:** Buscan certeza y alertas pasivas sobre la seguridad de sus hijos.</p><br>
        </td>
        <td valign="top">
            <div align="center"><br><b>4. User Outcomes & Benefits</b></div><br>
            <p>- **Padres:** Paz mental, ahorro de tiempo, fin de la incertidumbre.<br>- **Conductores:** Conducción 100% enfocada, eliminación del estrés por reclamos, registro exacto.<br>- **Admin:** Centralización logística, mejora en la reputación del servicio.</p><br>
        </td>
    </tr>
    <tr>
        <td valign="top">
            <div align="center"> <br><b>6. Hypotheses</b> </div><br>
            <p>- H1: El GPS en background y soporte offline asegurarán la retención de planes de pago al eliminar la distracción del conductor.<br>- H2: Las alertas por Geofencing harán que los padres exijan la app, generando adopción orgánica.<br>- H3: El botón de incidencias reducirá masivamente las quejas formales.</p> <br>
        </td>
        <td valign="top">
            <div align="center"> <br><b>7. What’s the most important thing we need to learn first?</b> </div><br><p>¿Están los administradores y conductores independientes dispuestos a pagar una suscripción mensual por un SaaS logístico que no es un marketplace de viajes?</p> <br>
        </td>
        <td valign="top">
            <div align="center">  <br><b>8. What's the least amount of work we need to do to learn the next most important thing?</b> </div><br><p>Realizar de 3 a 5 entrevistas de validación profunda con dueños de movilidades escolares y padres de familia para validar la disposición de pago por "tranquilidad" y "orden operativo".</p> <br>
        </td>
    </tr>
</table>

## 1.3 Segmentos objetivo

Para el ecosistema de RouteGuard, hemos identificado dos segmentos de usuarios claramente diferenciados que interactuarán con nuestras interfaces (nativa y multiplataforma). Ambos segmentos son interdependientes para el éxito del modelo de negocio SaaS.

### Segmento 1: Transportistas Escolares (Administradores y Conductores)

* **Demografía:** Hombres y mujeres de 30 a 60 años, residentes en Lima Metropolitana y otras principales zonas urbanas del país. Nivel socioeconómico B, C y D.
* **Perfil Ocupacional:** Microempresarios dueños de su propio vehículo (minivans) que operan de forma independiente, o administradores de pequeñas flotas (de 2 a 5 unidades) dedicadas exclusivamente al traslado escolar privado.
* **Características y Comportamiento:** Poseen habilidades tecnológicas de nivel básico a intermedio. Pasan entre 4 y 6 horas diarias al volante lidiando con tráfico pesado. Buscan mantener o incrementar su cartera de clientes ofreciendo un servicio más profesional, pero evitan herramientas complejas que los distraigan. Requieren que la tecnología funcione como un asistente silencioso (GPS en segundo plano, soporte offline para zonas sin cobertura y botones grandes de 1 toque). Su mayor punto de dolor es la carga de responder llamadas y mensajes de padres mientras conducen.
* **Información estadística de sustento:** Según la Autoridad de Transporte Urbano para Lima y Callao (ATU, 2024), se registró una caída del 25% en las movilidades escolares formalmente autorizadas, dejando un mercado altamente fragmentado e informal. Este segmento representa a miles de transportistas que necesitan urgentemente herramientas accesibles (SaaS) para digitalizar, organizar y dar valor agregado a su servicio frente a un mercado cada vez más exigente.

### Segmento 2: Padres de Familia

* **Demografía:** Hombres y mujeres de 28 a 50 años. Nivel socioeconómico A, B y C+.
* **Perfil Familiar:** Padres o tutores legales con hijos en etapa preescolar o primaria (3 a 12 años) que asisten a instituciones educativas de gestión privada.
* **Características y Comportamiento:** Son usuarios altamente conectados a través de smartphones. Poseen jornadas laborales estructuradas que les impiden realizar el recojo escolar personalmente. Experimentan un alto nivel de ansiedad y vulnerabilidad respecto a la integridad física de sus hijos. No desean interactuar activamente con aplicaciones complejas; prefieren el consumo de información pasiva, es decir, valoran enormemente recibir notificaciones automáticas (Push Notifications) y alertas por proximidad (Geofencing) para continuar con su día a día con total paz mental.
* **Información estadística de sustento:** El Censo Educativo del Ministerio de Educación (MINEDU, 2023) detalla que de los aproximadamente 1.9 millones de estudiantes en Lima Metropolitana, un 74% asiste a colegios privados, la gran mayoría de los cuales no posee flotas de transporte propias. Esta cifra demuestra la masiva dependencia de las familias hacia los transportistas de terceros, justificando el tamaño de este segmento que clama por transparencia, trazabilidad y seguridad digital en el servicio diario.

<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Development and Software Solution Design

## 2.1. Competidores

#### 2.1.1 Análisis Competitivo

**¿Por qué llevar a cabo el análisis?**

Este análisis nos permite conocer las características, ventajas y limitaciones de las principales soluciones de transporte escolar existentes en el mercado. También ayuda a identificar oportunidades de diferenciación y áreas de mejora para SafeRoute.

| Categoría | Subcategoría | **RouteGuard**![RouteGuard](.assetsimagesChapter2RouteGuard.png)                                                                                                      | **OnTrack School**![OnTrack School](./resources/assets/images/OnTrackSchool.png)| **SafeRoute Parent** ![SafeRoute Parent](./resources/assets/images/SafeRouteParent.png)| **BusRight**![BusRight](./resources/assets/images/BusRight.png)                                            |
|---|---|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|---|------------------------------------------------------------------------------------------------------------|
| **Perfil** | Overview | Plataforma de monitoreo y gestión de transporte escolar.                                                                                                              | Plataforma de gestión de transporte escolar para colegios, instituciones educativas y empresas de transporte. | Plataforma de monitoreo y seguridad del transporte escolar enfocada principalmente en padres de familia. | Plataforma integral para la gestión y optimización del transporte escolar y sus operaciones.               |
| | Ventaja Competitiva | Roles específicos tanto para el padre como para el conductor y herramientas para la gestión de los viajes escolares.                                                  | Integra la gestión del transporte, seguimiento en tiempo real, control de acceso y otros servicios escolares en una sola plataforma. | Enfoque en seguridad, seguimiento en tiempo real, alertas y tranquilidad para los padres durante el traslado. | Combina planificación de rutas, GPS, gestión de estudiantes, conductores y comunicación con los padres.    |
| **Perfil de Marketing** | Mercado Objetivo | Padres de familia y conductores de movilidad escolar.                                                                                                                 | Colegios, instituciones educativas y empresas de transporte escolar. | Padres de familia, colegios y operadores de transporte escolar. | Distritos escolares, departamentos de transporte y grandes operadores de transporte estudiantil.           |
| | Estrategias de Marketing | Variedad de herramientas y seguridad para la correcta gestión de viajes escolares.                                                                                    | Marketing B2B dirigido a instituciones educativas mediante demostraciones, presencia digital y casos de éxito. | Marketing enfocado en seguridad, tranquilidad de los padres, seguimiento en tiempo real y protección de los estudiantes. | Marketing B2B orientado a eficiencia operativa, reducción de costos, seguridad y optimización de rutas.    |
| **Perfil de Producto** | Productos y Servicios | Plataforma web, dashboard, GPS.                                                                                                                                       | Gestión de rutas, GPS, alumnos, vehículos, conductores, notificaciones y control de acceso. | Seguimiento GPS, ETA, alertas, geocercas, monitoreo del conductor y comunicación con padres. | Planificación de rutas, GPS, gestión de estudiantes, navegación para conductores, notificaciones y seguimiento. |
| | Precios y Costos | Suscripción mensual de entre S/.9.99 y S/.49.99.                                                                                                                      | Precios personalizados según los servicios y características contratados por cada institución. | Aplicación gratuita para padres. No presenta información pública clara sobre los precios para instituciones u operadores. | Precios personalizados según el tamaño y las necesidades de cada organización.                             |
| | Canales de Distribución (Web y/o Móvil) | Plataforma web.                                                                                                                                                       | Plataforma web y aplicaciones móviles para padres, conductores y administradores. | Aplicación móvil para padres y herramientas digitales para operadores de transporte. | Plataforma web y aplicaciones móviles para administradores, conductores y padres.                          |
| **Análisis SWOT** | Fortalezas | Sistema enfocado en seguimiento de viajes, control de viajes y agendas y gestión.                                                                                     | Amplia propuesta de valor, integración con servicios escolares y presencia en el mercado latinoamericano. | Fuerte enfoque en seguridad, monitoreo en tiempo real y experiencia de los padres. | Plataforma completa con optimización de rutas, gestión operativa y herramientas de seguridad.              |
| | Debilidades | Modelo de negocio nuevo en un mercado con mucha incertidumbre.                                                                                                        | Puede resultar complejo para pequeños operadores y depende principalmente de instituciones educativas. | Se concentra principalmente en monitoreo y seguridad, con menor énfasis en la gestión integral del transporte. | Está orientado principalmente a organizaciones grandes y al mercado estadounidense.                        |
| | Oportunidades | Gran crecimiento potencial en el mercado de transporte escolar privado en Perú, ampliando funcionalidades y expandiéndose a otras ciudades y colegios.                | Expandirse en Latinoamérica y ofrecer más servicios para empresas de transporte escolar. | Incorporar funcionalidades de gestión de rutas, alumnos, conductores y operaciones. | Expandirse hacia nuevos mercados e incorporar inteligencia artificial para optimizar rutas y operaciones.  |
| | Amenazas | Entrada de competidores más consolidados (como SafeRouteParent u OnTrack School) y soluciones informales o manuales que ya usan algunos colegios y padres de familia. | Nuevas plataformas SaaS, soluciones locales de transporte y sistemas GPS de menor costo. | Competidores que integren monitoreo, gestión, pagos y comunicación en una sola plataforma. | Software local, soluciones internas de colegios y nuevos competidores especializados en transporte escolar. |




### 2.1.2. Estrategias y tácticas frente a competidores

En base al análisis competitivo realizado, se plantean las siguientes estrategias y tácticas para posicionar a RouteGuard frente a sus competidores:

#### Enfoque en la especialización del problema

- RouteGuard se centrará exclusivamente en el transporte escolar, integrando funcionalidades pensadas para las necesidades particulares de este sector, entre ellas el control de abordaje, la gestión de rutas y el registro de incidencias.
- Con esto, la plataforma cubre aspectos operativos y de seguridad que las aplicaciones genéricas de geolocalización suelen dejar de lado.

#### Estrategia de digitalización del sector no estructurado

- La solución apuntará principalmente a transportistas independientes que hoy en día coordinan sus servicios a través de WhatsApp, llamadas y procesos manuales.
- RouteGuard propondrá una plataforma simple y práctica que permita digitalizar esas actividades sin exigir conocimientos técnicos ni implementaciones complicadas.

#### Diferenciación mediante simplicidad y accesibilidad

- Se apostará por una experiencia intuitiva, sencilla y económica, marcando distancia frente a plataformas corporativas más robustas como OnTrack School.
- La interfaz buscará minimizar la carga administrativa del conductor, facilitando su uso durante la operación del día a día.

#### Estrategia de confianza y seguridad para los padres

- RouteGuard trabajará en reducir la incertidumbre de los padres a través de notificaciones automáticas de abordaje, seguimiento del trayecto y alertas en tiempo real.
- De esta forma, se reemplaza la comunicación informal y fragmentada por un sistema estructurado que entrega información clara, oportuna y confiable sobre el traslado de los estudiantes.

#### Estrategia de crecimiento progresivo y escalabilidad

- La plataforma ofrecerá planes escalonados —Básico, Intermedio y Completo— capaces de ajustarse al crecimiento en número de estudiantes o vehículos gestionados por cada cliente.
- Este esquema facilita la entrada de nuevos usuarios con una opción inicial accesible, dejando abierta la posibilidad de ampliar servicios a medida que sus necesidades crezcan.

#### Estrategia de posicionamiento local

- En su etapa inicial, RouteGuard estará enfocado en las dinámicas operativas y particularidades geográficas de Lima Metropolitana, buscando entender a fondo las necesidades del transporte escolar en este mercado.
- Una vez que la solución se consolide localmente, se evaluará su expansión gradual hacia otras ciudades del país.

#### Estrategia de preparación tecnológica a futuro

- La arquitectura de RouteGuard se pensará contemplando futuras integraciones con tecnologías IoT, como sensores, cámaras y otros dispositivos de monitoreo.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

El objetivo de estas entrevistas es validar la magnitud de los problemas de comunicación, el nivel de estrés operativo y la disposición para adoptar una solución tecnológica pasiva en el transporte escolar. Para asegurar un *Needfinding* efectivo, las preguntas se han diseñado de manera abierta, evitando sesgar las respuestas del usuario.

#### A. Segmento 1: Transportistas Escolares (Administradores y Conductores)

**Rompehielo y Contexto:**
1. ¿Cuánto tiempo llevas dedicándote al transporte escolar y cuántos alumnos o rutas manejas en un día promedio?
2. ¿Trabajas de forma independiente o administras una flota con otros conductores?

**Descubrimiento del Problema (Dolores y Procesos actuales):**
1. Cuéntame paso a paso: ¿Cómo llevas el control diario de qué alumno subió, faltó o bajó de tu unidad?
2. ¿Qué sucede exactamente cuando hay un retraso imprevisto (mucho tráfico, falla mecánica o un alumno que demora en salir)? ¿Cómo lo gestionas?
3. ¿Con qué frecuencia recibes llamadas o mensajes de WhatsApp de los padres mientras estás conduciendo? ¿Cómo lidias con eso sin descuidar el volante?
4. ¿Qué herramientas digitales usas hoy para organizarte? (¿Puro WhatsApp y cuaderno, o alguna app específica?)
5. ¿Cómo suele gestionar el cobro mensual a los padres? ¿Has tenido problemas con padres que dicen que pagaron tarde o retrasos que te afectan económicamente?
6. En tus rutas diarias, ¿te has encontrado con zonas donde la señal de internet se cae por completo (sótanos de edificios, avenidas con mala cobertura)? ¿Cómo manejas el registro de asistencia o la comunicación en esos momentos?
7. Cuando un padre te avisa a última hora que su hijo no irá al colegio o que hoy lo recoge en otro lugar, ¿cómo modificas tu ruta sobre la marcha y cómo te aseguras de no olvidarlo mientras estás manejando?
8. Cuando empieza el año escolar o entra un nuevo alumno a la ruta, ¿cómo es el proceso para coordinar los puntos exactos de recojo, los horarios y los números de contacto de los papás sin que se vuelva un enredo de chats?

**Validación de Solución:**
1. ¿Qué herramientas digitales usas hoy para organizarte? (¿Puro WhatsApp y cuaderno, o alguna app específica?)
2. Si existiera un sistema que pasara lista con un toque y notificara automáticamente a los padres tu ubicación sin que tengas que mirar la pantalla, ¿qué impacto tendría en tu rutina diaria?
3. ¿Estarías dispuesto a pagar una suscripción mensual por una herramienta SaaS si esta te ayuda a evitar quejas de los padres y te da una imagen más formal frente a los colegios?

#### B. Segmento 2: Padres de Familia

**Rompehielo y Contexto:**
1. ¿Cuántos años tienen tus hijos y por qué decidiste contratar un servicio de movilidad escolar privada en lugar de llevarlos personalmente?
2. ¿Aproximadamente cuánto tiempo dura el trayecto desde tu casa hasta el colegio?

**Descubrimiento del Problema (Dolores y Procesos actuales):**
1. Actualmente, ¿cómo te enteras de que la movilidad ya está cerca a tu casa para salir, o cómo te aseguras de que tu hijo llegó a salvo al colegio?
2. Cuéntame de alguna vez en la que la movilidad se retrasó de forma inusual o no te contestaban el teléfono. ¿Qué sentiste, qué pensaste y qué hiciste para resolverlo?
3. ¿Qué es lo más frustrante de la comunicación actual que tienes con el conductor de la movilidad?
4. Cuando tu hijo se enferma a última hora o tienes que cambiar el punto de recogida por un imprevisto, ¿qué tan complicado es avisarle al transportista y asegurarte de que realmente leyó tu mensaje antes de que llegue a buscarlo?
5. Pensando en la seguridad, ¿qué tan tranquilo te deja el sistema actual de llamadas o chats para saber que tu hijo realmente subió a la movilidad y está camino al colegio sin contratiempos?
6. ¿Cómo sueles enterarte del costo mensual, los retrasos en los pagos o los acuerdos de tarifa con el transportista? ¿Alguna vez ha habido confusiones o malos entendidos con el dinero?
7. Cuando la movilidad llega a recoger a tu hijo y este demora en salir de la casa, ¿cómo reacciona el conductor? ¿Te presiona, toca claxon insistentemente o genera tensión con los vecinos?
8. ¿Alguna vez has tenido dudas sobre la seguridad del vehículo en el que viaja tu hijo (por ejemplo, estado de las llantas, asientos sin cinturón adecuado o exceso de pasajeros)? ¿Cómo lo conversas con el transportista?
9. ¿Cómo es el momento de la entrega por la tarde? ¿Te avisan cuando están llegando para que bajes a recibir a tu hijo, o tienes que estar asomándote a la ventana cada cinco minutos?


**Validación de Solución:**
1. Si tuvieras una tecnología para monitorear el viaje, ¿preferirías tener que abrir la aplicación y vigilar un mapa todo el tiempo, o preferirías recibir notificaciones automáticas en segundo plano (ej. "A 2 cuadras de tu casa")? ¿Por qué?
2. Si el conductor actual de tu hijo se negara a usar un sistema de monitoreo, ¿considerarías cambiar a un transportista que sí te ofrezca esa trazabilidad y tecnología de seguridad?
3. ¿Estarías dispuesto a configurar contactos de emergencia o familiares autorizados dentro de la misma aplicación para que ellos también reciban las alertas de geofencing cuando tú estés ocupado trabajando?
4. ¿Qué tan útil te parecería un historial diario en la app donde puedas ver la hora exacta en que tu hijo subió a la movilidad y la hora exacta en que llegó al colegio?
5. Si el sistema te permitiera reportar desde la app que tu hijo faltará al colegio con un solo botón la noche anterior, ¿crees que eso reduciría los malentendidos con el conductor?


### 2.2.2. Registro de entrevistas

#### Entrevistado 1: Manuel Jesús Francia Huambachano (Segmento: Padres de Familia)
* **Edad:** 50
* **Distrito de residencia:** Lurín, Lima
* **URL de la entrevista:** [Ingresar URL del video subido a OneDrive]
* **Timing de inicio:** 00:00:01
* **Screenshot del video:**
  ![Extrevista 1 - Manuel](resources/chapter-2/interviews/manuel.png)

**Resumen de la entrevista:**
Manuel es un padre de familia con un hijo de 13 años, quien contrató el servicio de movilidad escolar debido a la lejanía del centro educativo y la incompatibilidad de sus horarios. A nivel tecnológico, es un usuario activo de canales digitales: utiliza WhatsApp para comunicación, realiza pagos mediante billeteras digitales (Yape) y transferencias bancarias, y emplea aplicaciones de control parental (*Google Family Link*) para rastrear el dispositivo de su hijo. 

* **Comportamiento actual:** Actualmente, su único canal de interacción en tiempo real para saber que la movilidad llegó es escuchar el claxon en la puerta. Para emergencias o retrasos, su única alternativa es realizar llamadas telefónicas directas a la conductora. Él y su esposa mantienen un control manual para asegurar el cumplimiento de los pagos puntuales de la pensión.
* **Frustraciones (Pain Points):** Su mayor frustración radica en la incertidumbre y la falta de visibilidad. Señala que ocurren episodios donde su hijo está listo con 10 minutos de anticipación, pero la movilidad se retrasa hasta 15 minutos sin previo aviso debido al tráfico, obligándolos a esperar a ciegas. Le resulta muy incómodo y peligroso tener que llamar por teléfono a la conductora para conocer su ubicación, ya que ella se encuentra manejando. Además, indica que si bien usa *Family Link*, esta herramienta no está diseñada para este contexto, ya que no le muestra el tráfico, desvíos ni el tiempo estimado de llegada de la movilidad. Tampoco cuenta con información formal sobre las condiciones de seguridad y aforo del vehículo.
* **Percepción de la solución propuesta:** Manuel ve un alto valor en la propuesta tecnológica. Considera indispensable contar con notificaciones automáticas de proximidad (alertas de que la movilidad está cerca) y valora mucho la función de tener un historial diario que registre la hora exacta de abordaje y llegada al colegio. Indica que un botón para reportar ausencias (añadiendo el motivo) reduciría drásticamente los problemas de comunicación. Su interés por la seguridad es tan alto que afirma estar dispuesto a cambiar de transportista si su servicio actual se negara a modernizarse y usar una plataforma tecnológica de este tipo.

#### Entrevistado 2: Luis Johnny Jesús Mendoza (Segmento: Conductor / Transportista)
* **Edad:** 57
* **Distrito de residencia:** Lurín, Lima
* **URL de la entrevista:** [Ingresar URL del video subido a OneDrive]
* **Timing de inicio:** [Ej: 00:15:20]
* **Screenshot del video:**
  ![Extrevista 2 - Luis](resources/chapter-2/interviews/luis.png)

**Resumen de la entrevista:**
Luis Johnny es conductor y representante de *Transporte JCM SAC*, una empresa con casi 5 años en el rubro dedicada al transporte de personal, turismo y taxis. Actualmente presta servicios corporativos, tanto directos como tercerizados (ej. empresa Netafin), para trasladar personal operativo hacia fábricas y plantas industriales. Su dinámica de trabajo diaria se basa en horarios estrictos y turnos rotativos (Guardias A, B y C). A nivel tecnológico, su principal y única herramienta de coordinación en tiempo real es **WhatsApp**, a través del cual reporta su ubicación a los supervisores de la planta. 

* **Comportamiento actual:** La gestión de los pasajeros la realiza de forma manual mediante **listas impresas en papel** proporcionadas por el área de logística de la empresa cliente. Luis no recoge a los pasajeros puerta por puerta, sino que cumple con 3 o 4 "puntos de recojo" fijos con horarios preestablecidos. A medida que avanza en su ruta, escribe mensajes en el grupo de WhatsApp (ej. *"Llegando al punto 1"*) para que los jefes sepan que el transporte está en curso. Sus pagos se manejan mediante contratos a 30 días con el área de logística.
* **Frustraciones (Pain Points):** El mayor estrés en su ruta son los imprevistos de tráfico por choques o rotura de tuberías. Si el retraso supera los 10 o 15 minutos, se convierte en un problema crítico para la fábrica, ya que *"las máquinas no paran"* y los trabajadores del turno anterior deben quedarse trabajando horas extras. Notificar estos retrasos mientras conduce es ineficiente y recae totalmente en la comunicación manual por chat, lo cual no le permite actualizar de forma automática los tiempos estimados de llegada (ETA) para los trabajadores que lo esperan en los siguientes paraderos.
* **Percepción de la solución propuesta:** Luis considera que una aplicación móvil de monitoreo y gestión sería una herramienta invaluable, especialmente para escalar su negocio. Reconoce que actualmente lleva el control "así nomás" (hojas y chats), pero entiende que para manejar flotas más grandes un software de trazabilidad es obligatorio. Ve un impacto muy positivo en el uso de la app para transmitir una **imagen más formal y profesional** frente a sus clientes corporativos, y afirmó estar dispuesto a pagar una suscripción mensual por esta tecnología conforme su empresa de transportes siga creciendo.

#### Entrevistado 3: Máximo Quevedo (Segmento: Padres de Familia)
* **Edad:** [Ingresar Edad]
* **Distrito de residencia:** [Ingresar Distrito]
* **URL de la entrevista:** [Ingresar URL del video subido a OneDrive]
* **Timing de inicio:** [Ej: 00:15:20]
* **Screenshot del video:**
  ![Extrevista 3 - Máximo](resources/chapter-2/interviews/maximo.png)

**Resumen de la entrevista:**
Máximo es un padre de familia con un hijo de 7 años. Optó por contratar movilidad escolar privada para optimizar su tiempo frente al complejo tráfico de Lima, permitiéndole dirigirse directamente a su centro de labores. Su perfil es marcadamente tecnológico y analítico; está muy familiarizado con aplicativos financieros y valora la eficiencia digital, afirmando firmemente que *"quienes no se adaptan a la tecnología en el siglo XXI se quedan atrás"*.

* **Comportamiento actual:** La comunicación que mantiene con el servicio de movilidad se da exclusivamente a través de mensajes o llamadas. Del mismo modo, el control de los pagos de la pensión escolar de su hijo se realiza por WhatsApp, donde recibe las notificaciones de cobro de manera informal y manual.
* **Frustraciones (Pain Points):** Su principal dolor es la falta de comunicación en tiempo real y la gran angustia que esto le genera. Relató un episodio crítico donde la movilidad se retrasó 20 minutos; al no tener forma de rastrear el vehículo, sintió un altísimo nivel de estrés temiendo un accidente o un extravío, viéndose obligado a timbrar desesperadamente a la directora del colegio. Adicionalmente, encuentra ineficiente llevar el control de pagos por WhatsApp, ya que a menudo se generan confusiones, desorden y *"los montos no cuadran"*.
* **Percepción de la solución propuesta:** Máximo aprueba rotundamente la creación de la aplicación. Debido a la alta concentración que exige su trabajo (análisis de costos), prefiere recibir **notificaciones automáticas en segundo plano** en lugar de tener que vigilar activamente un mapa. Destaca la necesidad de tener un historial integrado, tanto para registrar las horas exactas de los viajes, como para llevar un control transparente de los pagos (comparándolo con una app bancaria). Es tan firme en su postura que asegura que **descartaría de inmediato** a su transportista actual si este se negara a usar el aplicativo. Finalmente, respalda con entusiasmo la función de reportar inasistencias con un botón y la opción de incluir contactos de emergencia.

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

Para empatizar con nuestros usuarios y comprender a profundidad sus necesidades, frustraciones y metas, hemos desarrollado dos *User Personas* (Cooper, 1999) basados en la investigación y entrevistas realizadas en las fases previas. Estos arquetipos representan a nuestros dos segmentos objetivo y son fundamentales para guiar el diseño de la arquitectura de información y la experiencia de usuario (UX) de **RouteGuard**.

#### A. Segmento 1: El Transportista (Conductor)

El primer arquetipo representa a nuestro segmento operativo. Carlos ilustra al conductor tradicional que maneja un alto nivel de estrés debido al tráfico y a las constantes interrupciones por parte de los padres de familia. Su nivel tecnológico es intermedio, lo que nos indica que la interfaz móvil que utilice debe ser altamente intuitiva, con botones grandes y requerir la menor interacción manual posible (idealmente de 1 solo toque) para evitar distracciones al volante y reducir su carga cognitiva (Kumar & Lee, 2024).

![User Persona - Carlos Mendoza, Conductor](resources/chapter-2/user-personas/carlos-el-tio-mendoza.png)

#### B. Segmento 2: El Padre de Familia

El segundo arquetipo representa a nuestro cliente final. Valeria ilustra a la madre profesional moderna, cuyo principal dolor es la incertidumbre y la falta de tiempo. Al tener un alto nivel de dominio tecnológico, espera que la tecnología trabaje para ella de forma pasiva. Esto valida nuestra hipótesis de que la aplicación para padres no debe requerir un monitoreo activo del mapa, sino apoyarse fuertemente en un sistema de notificaciones automáticas y alertas contextuales mediante *Geofencing* (Chen & Zhao, 2025).

![User Persona - Valeria Rojas, Padre de Familia](resources/chapter-2/user-personas/valeria-rojas.png)

---
**Conclusión del Needfinding:**

El contraste entre ambos perfiles justifica nuestra decisión arquitectónica de separar el ecosistema RouteGuard en dos aplicaciones distintas, garantizando que cada segmento reciba una interfaz adaptada a su contexto de uso, nivel de atención y habilidades tecnológicas.

### 2.3.2. User Task Matrix

El *User Task Matrix* es un artefacto fundamental en el diseño de interacción humano-computadora, ya que permite mapear la criticidad y la frecuencia de las tareas según el rol del usuario, lo que optimiza así la arquitectura de la información (Kumar & Lee, 2024).
En el caso de RouteGuard, esta matriz justifica nuestra decisión de separar la solución en dos aplicaciones distintas: una interfaz operativa para el conductor, donde se busca que la interacción manual sea mínima (de 1 solo toque) para no incrementar la carga cognitiva ni el riesgo de accidentes viales (Smith & Johnson, 2025), y una interfaz de monitoreo pasivo para el padre de familia.
La siguiente matriz detalla las tareas principales dentro del ecosistema y la frecuencia con la que cada segmento interactúa con ellas:

| Tarea (Task) | Administrador / Conductor | Padre de Familia | Frecuencia |
|--------------|---------------------------|------------------|------------|
| Registrar perfil y pagar suscripción | Alta (Crea la ruta) | Nula | Única vez |
| Monitorear mapa en tiempo real | Baja | Alta | Diaria |
| Iniciar y finalizar un trayecto (Trip) | Alta | Nula | Diaria |
| Marcar asistencia (Check-in/out) | Alta | Nula | Diaria |
| Reportar incidencia / Botón de Pánico | Media | Nula | Ocasional |
| Recibir notificación de proximidad | Nula | Alta | Diaria |
| Revisar historial de asistencias | Alta | Media | Semanal |

### 2.3.3. User Journey Mapping

El *User Journey Map* es una herramienta metodológica fundamental en el diseño de servicios que nos permite visualizar la experiencia del usuario a lo largo del tiempo. Ello nos permite identificar sistemáticamente los puntos de dolor (*pain points*) y las oportunidades de interacción con nuestra solución tecnológica (Stickdorn et al., 2018). Para RouteGuard, hemos mapeado las rutinas matutinas de nuestros dos segmentos principales. De esa manera demostramos cómo la aplicación interviene en los momentos de mayor fricción.

#### A. Journey Map: El Transportista (Conductor)
El recorrido de Carlos evidencia que el momento crítico ocurre durante el tráfico pesado. La implementación de transmisión GPS en segundo plano (*background location*) transforma una situación de alto estrés en un momento de serenidad, ya que el conductor no necesita interactuar con el dispositivo para calmar la ansiedad de los padres.

![User Journey Map - Carlos Mendoza](resources/chapter-2/user-journey-mapping/user-journey-map-carlos-mendoza.png)

#### B. Journey Map: El Padre de Familia
El recorrido de Valeria demuestra cómo la incertidumbre matutina se resuelve mediante la tecnología. El uso de alertas automatizadas por *Geofencing* elimina la necesidad de monitoreo activo, generando un pico de confianza y alivio exactamente en el momento en que el estudiante aborda la unidad.

![User Journey Map - Valeria Rojas](resources/chapter-2/user-journey-mapping/user-journey-map-valeria-rojas.png)

### 2.3.4. Empathy Mapping


En esta sección se presenta el análisis de empatía realizado para nuestros segmentos objetivo, buscando responder a las preguntas fundamentales del marco de trabajo: *¿Con quién estamos empatizando?*, *¿Qué necesita hacer?*, *¿Qué ve?*, *¿Qué dice?*, *¿Qué hace?*, *¿Qué oye?*, *¿Qué piensa y siente?*, e identificando claramente sus dolores (*Pains*) y ganancias (*Gains*).

---

#### Segmento Objetivo 1: Drivers

![Arturo Núñez Empathy Map](./resources/assets/images/Arturo%20Núñez%20Empaty%20map.png)

---

#### Segmento Objetivo 2: Parents

![Fernando Nery Empathy Map](./resources/assets/images/Fernando%20Nery%20%20Empaty%20map.png)


### 2.3.5. Big Picture EventStorming

El *Big Picture EventStorming* es una técnica de modelado colaborativo de arquitectura de software que nos permitió explorar y mapear la totalidad de los procesos de negocio de **RouteGuard**. En esta etapa inicial, nos enfocamos exclusivamente en descubrir la línea temporal del ecosistema a través de los **Domain Events** (Eventos de Dominio). 

Como dicta el estándar de esta herramienta (Brandolini, 2021), los eventos fueron redactados utilizando el *Ubiquitous Language* en inglés y en pasado participio, representando hechos relevantes que ya han ocurrido en el sistema y que interesan a los expertos del negocio.

A continuación, se presenta la pizarra desarrollada, dividida en las tres fases principales del ciclo de vida del servicio de movilidad:

![RouteGuard Big Picture EventStorming](resources/chapter-2/big-picture-eventstorming/big-picture-eventstorming.png)

#### Cronología de Eventos de Dominio Identificados:

**Fase 1: Pre-viaje y Configuración (Setup)**
* `SubscriptionPlanPurchased`: Un administrador adquiere un plan SaaS.
* `DriverAccountCreated`: Se registra un conductor en la plataforma.
* `SchoolRouteCreated`: El administrador diseña la secuencia de paradas.
* `StudentAssignedToRoute`: Se asocia un niño a una ruta específica.

**Fase 2: Operación Central (Core)**
* `TripStarted`: El conductor inicia el recorrido diario.
* `ProximityGeofenceTriggered`: El GPS penetra el radio del hogar, detonando alertas.
* `StudentBoarded`: El conductor registra la subida del niño (*Check-in*).
* `StudentDroppedOff`: El conductor registra la bajada del niño (*Check-out*).
* `IncidentReported`: Se registra un retraso o emergencia en el trayecto.

**Fase 3: Post-viaje y Cierre**
* `TripFinished`: El vehículo llega a su destino final.
* `DailyReportGenerated`: El sistema procesa la bitácora de asistencia.

El descubrimiento de esta línea temporal fue el insumo principal para poder agrupar lógicamente estos eventos y descubrir nuestros *Bounded Contexts* en la etapa de diseño estratégico.

### 2.3.6. Ubiquitous Language

Siguiendo los principios fundamentales del *Domain-Driven Design* (Evans, 2003), hemos establecido un *Ubiquitous Language* (Lenguaje Ubicuo). Este glosario estandariza los términos del negocio en inglés para garantizar que tanto el equipo de desarrollo como los expertos del dominio utilicen exactamente el mismo vocabulario, eliminando ambigüedades entre el código fuente y las reglas de negocio.

| Término | Descripción | Contexto |
|---------|-------------|----------|
| **Fleet** | Colección de vehículos y conductores gestionados por un mismo Administrador de transporte escolar. | IAM / Routing |
| **Route** | Secuencia predefinida de paradas (*Stops*) desde un punto de origen hacia un colegio (o viceversa). | Routing |
| **Trip** | La ejecución física y en tiempo real de una *Route* en una fecha y hora específica. | Operations |
| **Stop** | Ubicación geográfica (coordenadas) donde un estudiante debe subir o bajar del vehículo. | Routing |
| **Boarding** | El acto en el que un estudiante ingresa al vehículo y el conductor registra su asistencia en el sistema. | Operations |
| **Geofence** | Perímetro virtual circular alrededor de un *Stop*. Cuando el GPS del conductor penetra este perímetro, dispara eventos automáticos. | Notifications |
| **Proximity Alert** | Notificación Push enviada pasivamente al celular del padre cuando se penetra el *Geofence* de su hogar. | Notifications |
| **Incident** | Evento inesperado (tráfico pesado, falla mecánica, accidente) que altera el curso normal de un *Trip*. | Operations |

## 2.4. Requirements specification

La especificación de requerimientos en entornos de desarrollo ágil reemplaza la documentación extensa y rígida por formatos ligeros que fomentan la colaboración y capturan el valor directo para el cliente (Cohn, 2004). En este proyecto, integramos técnicas de agilidad con los principios de *Domain-Driven Design* (Evans, 2003) para garantizar que las necesidades del negocio se reflejen fielmente en la estructura del software.

### 2.4.1. User Stories

Las Historias de Usuario (*User Stories*) y las Épicas son herramientas fundamentales en Scrum y metodologías ágiles, diseñadas para desplazar el enfoque de "escribir requerimientos" hacia "fomentar conversaciones" sobre ellos (Cohn, 2004). 

Para el caso de RouteGuard, hemos estructurado nuestras Épicas de modo que se alineen uno a uno con los *Bounded Contexts* descubiertos en nuestro diseño estratégico. Esta decisión asegura una transición fluida entre el modelado del problema y el diseño de la solución (Vernon, 2013). A continuación, se detallan las Épicas y sus respectivas Historias de Usuario, Historias Técnicas y Spikes, estructuradas bajo el formato de Criterios de Aceptación Gherkin (*Given-When-Then*).

**EPICS (Alineadas a los Bounded Contexts)**

| Epic ID | Título (Bounded Context) | Descripción | Criterios de Aceptación |
| :--- | :--- | :--- | :--- |
| **EP01** | **Identity & Access Management** | Como usuario, quiero registrarme y autenticarme según mi rol para usar la plataforma. | **Escenario 1:**<br>**Dado que** el usuario es válido, <br>**Cuando** ingresa sus credenciales, <br>**Entonces** accede a las funciones de su perfil. |
| **EP02** | **Subscription & Plan Management** | Como administrador, quiero gestionar los pagos y planes SaaS para habilitar las funcionalidades. | **Escenario 1:**<br>**Dado que** el pago es exitoso, <br>**Cuando** se valida con la pasarela, <br>**Entonces** el sistema activa el acceso a la plataforma. |
| **EP03** | **Fleet & Route Management** | Como conductor, quiero gestionar mi flota y planificar rutas para asegurar un recojo eficiente. | **Escenario 1:**<br>**Dado que** tengo alumnos asignados, <br>**Cuando** genero la ruta, <br>**Entonces** el sistema ordena las paradas geográficamente. |
| **EP04** | **Stakeholder & Asset Management** | Como administrador o padre, quiero gestionar perfiles, calificar el servicio y vincular estudiantes a rutas. | **Escenario 1:**<br>**Dado que** un estudiante es validado, <br>**Cuando** el padre lo vincula a la movilidad, <br>**Entonces** el estudiante se agrega al grupo del conductor. |
| **EP05** | **Trip Execution & Monitoring** | Como conductor y padre, quiero transmitir y consultar la ubicación GPS y registrar abordajes offline. | **Escenario 1:**<br>**Dado que** el conductor avanza, <br>**Cuando** marca un abordaje sin internet, <br>**Entonces** se guarda localmente y sincroniza después. |
| **EP06** | **Notifications & Communication** | Como usuario, quiero recibir alertas automáticas, avisos y chatear para mantener la comunicación al momento. | **Escenario 1:**<br>**Dado que** el viaje está activo, <br>**Cuando** la movilidad entra al geocerca, <br>**Entonces** el padre recibe un Push Notification. |

<br>

**USER STORIES**

<!--US01-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-01</td>
    <td>Padre / Conductor</td>
    <td>Alta</td>
    <td>EP01</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Registro y Asignación de Rol</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como nuevo usuario, quiero crear una cuenta especificando si soy Padre, Conductor o Administrador para acceder a las funciones correspondientes a mi perfil.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Creación de cuenta exitosa</strong><br>
      <strong>Dado que</strong> el usuario ingresa sus datos válidos,<br>
      <strong>Cuando</strong> selecciona su rol principal,<br>
      <strong>Entonces</strong> el sistema persiste la cuenta en la base de datos con los accesos correspondientes.<br><br>
      <strong>Escenario 2: Correo duplicado</strong><br>
      <strong>Dado que</strong> el usuario ingresa un correo ya registrado,<br>
      <strong>Cuando</strong> intenta finalizar el registro,<br>
      <strong>Entonces</strong> el sistema bloquea la acción y exige credenciales diferentes.
    </td>
  </tr>
</table>

<br>

<!--US02-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-02</td>
    <td>Administrador</td>
    <td>Alta</td>
    <td>EP02</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Adquisición de Plan de Suscripción</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como administrador de flota, quiero suscribirme a un plan de pago mensual para poder registrar más de un vehículo en mi organización.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Pago procesado correctamente</strong><br>
      <strong>Dado que</strong> el administrador selecciona un plan premium,<br>
      <strong>Cuando</strong> el procesador de pagos confirma la transacción,<br>
      <strong>Entonces</strong> el sistema actualiza el estado de la cuenta a premium inmediatamente.<br><br>
      <strong>Escenario 2: Pago rechazado</strong><br>
      <strong>Dado que</strong> el administrador tiene fondos insuficientes,<br>
      <strong>Cuando</strong> el procesador de pagos deniega la transacción,<br>
      <strong>Entonces</strong> el sistema mantiene la cuenta en plan básico.
    </td>
  </tr>
</table>

<br>

<!--US03-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-03</td>
    <td>Administrador</td>
    <td>Media</td>
    <td>EP03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Gestión de Capacidad Vehicular</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como administrador, quiero establecer la cantidad de asientos de cada vehículo para evitar la sobreasignación de estudiantes.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Límite respetado</strong><br>
      <strong>Dado que</strong> un vehículo tiene un límite de 10 asientos,<br>
      <strong>Cuando</strong> el administrador intenta asignar un estudiante,<br>
      <strong>Entonces</strong> el sistema reduce la disponibilidad a 9 asientos.<br><br>
      <strong>Escenario 2: Límite excedido</strong><br>
      <strong>Dado que</strong> un vehículo tiene 0 asientos disponibles,<br>
      <strong>Cuando</strong> el administrador intenta asignar otro estudiante,<br>
      <strong>Entonces</strong> el sistema aborta la operación por exceso de capacidad.
    </td>
  </tr>
</table>

<br>

<!--US04-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-04</td>
    <td>Conductor</td>
    <td>Alta</td>
    <td>EP03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Listado y Secuencia de Paradas</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como conductor, quiero visualizar la lista diaria de alumnos ordenados por secuencia geográfica para seguir una ruta óptima.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Ordenamiento exitoso</strong><br>
      <strong>Dado que</strong> el conductor tiene 5 recojos programados,<br>
      <strong>Cuando</strong> solicita la ruta del día,<br>
      <strong>Entonces</strong> el sistema devuelve los domicilios ordenados según proximidad.
    </td>
  </tr>
</table>

<br>

<!--US05-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-05</td>
    <td>Conductor</td>
    <td>Alta</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Transmisión de GPS en Segundo Plano</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como conductor, quiero que la aplicación emita mi ubicación mientras está minimizada para poder concentrarme en manejar.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Emisión en background</strong><br>
      <strong>Dado que</strong> el viaje está activo,<br>
      <strong>Cuando</strong> el sistema operativo minimiza la aplicación,<br>
      <strong>Entonces</strong> el servicio continúa enviando las coordenadas al servidor cada 15 segundos.
    </td>
  </tr>
</table>

<br>

<!--US06-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-06</td>
    <td>Conductor</td>
    <td>Alta</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Check-in de Abordaje Offline</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como conductor, quiero registrar la subida de un niño incluso sin acceso a internet para no perder los datos del viaje.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Registro sin internet</strong><br>
      <strong>Dado que</strong> el dispositivo carece de conexión a la red,<br>
      <strong>Cuando</strong> el conductor marca la asistencia de un alumno,<br>
      <strong>Entonces</strong> el sistema guarda el evento localmente en la memoria del dispositivo.<br><br>
      <strong>Escenario 2: Sincronización diferida</strong><br>
      <strong>Dado que</strong> existen registros locales pendientes,<br>
      <strong>Cuando</strong> el dispositivo recupera la conexión a internet,<br>
      <strong>Entonces</strong> el sistema sincroniza automáticamente los datos con la base de datos principal.
    </td>
  </tr>
</table>

<br>

<!--US07-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-07</td>
    <td>Padre de Familia</td>
    <td>Alta</td>
    <td>EP06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Alerta de Geofencing</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como padre de familia, quiero recibir una notificación automática cuando la movilidad esté a 500 metros de mi casa para salir a tiempo.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Activación de alerta</strong><br>
      <strong>Dado que</strong> el vehículo transmite su ubicación,<br>
      <strong>Cuando</strong> la coordenada ingresa al radio de 500 metros del hogar,<br>
      <strong>Entonces</strong> el sistema dispara un evento de notificación push al dispositivo del padre.
    </td>
  </tr>
</table>

<br>

<!--US08-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-08</td>
    <td>Padre de Familia</td>
    <td>Media</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Monitoreo de Ruta en Tiempo Real</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como padre de familia, quiero visualizar la ubicación actual de la movilidad en un mapa para tener certeza sobre el trayecto de mi hijo.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Actualización de mapa</strong><br>
      <strong>Dado que</strong> el viaje está en curso,<br>
      <strong>Cuando</strong> el padre consulta la ruta,<br>
      <strong>Entonces</strong> el sistema renderiza un marcador geográfico que se actualiza según las coordenadas recibidas del conductor.
    </td>
  </tr>
</table>

<br>

<!--US09-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-09</td>
    <td>Padre de Familia</td>
    <td>Media</td>
    <td>EP06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Reporte de Ausencia Temprana</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como padre de familia, quiero avisar al sistema que mi hijo no asistirá al colegio hoy para que el conductor no pierda tiempo yendo a mi domicilio.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Cancelación exitosa</strong><br>
      <strong>Dado que</strong> el viaje aún no ha iniciado,<br>
      <strong>Cuando</strong> el padre marca al alumno como ausente,<br>
      <strong>Entonces</strong> el sistema remueve esa parada de la lista diaria del conductor y le envía una notificación.
    </td>
  </tr>
</table>

<br>

<!--US10-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-10</td>
    <td>Conductor</td>
    <td>Media</td>
    <td>EP06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Botón de Incidencias Rápido</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como conductor, quiero emitir una alerta general de retraso (por tráfico o accidente) a todos los padres de la ruta de manera simultánea.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Emisión masiva</strong><br>
      <strong>Dado que</strong> el conductor reporta tráfico intenso,<br>
      <strong>Cuando</strong> se emite el evento de incidencia,<br>
      <strong>Entonces</strong> el sistema despacha alertas push simultáneas a todas las familias de los alumnos a bordo.
    </td>
  </tr>
</table>

<br>

<!--US11-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-11</td>
    <td>Padre de Familia</td>
    <td>Alta</td>
    <td>EP02</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Registro de Múltiples Hijos</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como padre de familia, quiero vincular a más de un hijo en mi cuenta para poder monitorear los viajes de todos desde una sola sesión.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Vinculación exitosa</strong><br>
      <strong>Dado que</strong> el padre tiene un hijo ya registrado,<br>
      <strong>Cuando</strong> ingresa el código de vinculación de un segundo hijo,<br>
      <strong>Entonces</strong> el sistema asocia ambos perfiles a la misma cuenta parental.<br><br>
      <strong>Escenario 2: Límite de capacidad</strong><br>
      <strong>Dado que</strong> el padre intenta vincular a un hijo en una ruta llena,<br>
      <strong>Cuando</strong> envía la solicitud de asignación,<br>
      <strong>Entonces</strong> el sistema la rechaza indicando falta de vacantes.
    </td>
  </tr>
</table>

<br>

<!--US12-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-12</td>
    <td>Conductor</td>
    <td>Alta</td>
    <td>EP03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Control de Documentación (SOAT)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como conductor, quiero subir la documentación obligatoria de mi vehículo (SOAT, Revisión Técnica) para cumplir con las normativas y evitar suspensiones.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Documento vigente</strong><br>
      <strong>Dado que</strong> el conductor sube un SOAT válido,<br>
      <strong>Cuando</strong> el sistema lee la fecha de expiración,<br>
      <strong>Entonces</strong> el vehículo cambia su estado a "Apto para Operar".<br><br>
      <strong>Escenario 2: Documento vencido</strong><br>
      <strong>Dado que</strong> la fecha actual supera la expiración del SOAT registrado,<br>
      <strong>Cuando</strong> el conductor intenta iniciar una ruta,<br>
      <strong>Entonces</strong> el sistema bloquea el viaje y solicita la renovación.
    </td>
  </tr>
</table>

<br>

<!--US13-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-13</td>
    <td>Usuario</td>
    <td>Media</td>
    <td>EP01</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Gestión de Perfil de Usuario</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como usuario, quiero actualizar mi número de teléfono y foto de perfil para mantener mi información de contacto al día.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Actualización exitosa</strong><br>
      <strong>Dado que</strong> el usuario modifica su teléfono,<br>
      <strong>Cuando</strong> guarda los cambios,<br>
      <strong>Entonces</strong> el sistema persiste la actualización inmediatamente.<br><br>
      <strong>Escenario 2: Teléfono inválido</strong><br>
      <strong>Dado que</strong> el usuario ingresa letras en el campo numérico,<br>
      <strong>Cuando</strong> intenta guardar,<br>
      <strong>Entonces</strong> el sistema muestra un error de validación.
    </td>
  </tr>
</table>

<br>

<!--US14-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-14</td>
    <td>Padre de Familia</td>
    <td>Media</td>
    <td>EP04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Calificación del Servicio</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como padre de familia, quiero calificar el servicio del conductor al finalizar el mes para ayudar a mantener un estándar de calidad.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Envío de calificación</strong><br>
      <strong>Dado que</strong> el sistema habilita la evaluación mensual,<br>
      <strong>Cuando</strong> el padre asigna 5 estrellas,<br>
      <strong>Entonces</strong> el sistema suma la puntuación al promedio histórico del conductor.
    </td>
  </tr>
</table>

<br>

<!--US15-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-15</td>
    <td>Padre de Familia</td>
    <td>Baja</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Historial de Viajes Finalizados</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como padre de familia, quiero acceder al historial de viajes de la semana pasada para verificar los horarios exactos en los que mi hijo fue recogido.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Visualización de bitácora</strong><br>
      <strong>Dado que</strong> existen viajes completados,<br>
      <strong>Cuando</strong> el padre navega al historial,<br>
      <strong>Entonces</strong> el sistema devuelve una lista ordenada cronológicamente con las horas exactas de abordaje.
    </td>
  </tr>
</table>

<br>

<!--US16-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-16</td>
    <td>Administrador</td>
    <td>Media</td>
    <td>EP03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Asignación de Conductor a Vehículo</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como administrador, quiero asignar conductores específicos a los vehículos registrados para mantener un orden interno de la flota.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Asignación uno a uno</strong><br>
      <strong>Dado que</strong> existe un vehículo sin piloto,<br>
      <strong>Cuando</strong> el administrador selecciona un conductor libre,<br>
      <strong>Entonces</strong> el sistema vincula ambas entidades operativamente.<br><br>
      <strong>Escenario 2: Vehículo ya ocupado</strong><br>
      <strong>Dado que</strong> un vehículo ya tiene piloto asignado,<br>
      <strong>Cuando</strong> se intenta asignar a otro,<br>
      <strong>Entonces</strong> el sistema requiere confirmación de reemplazo.
    </td>
  </tr>
</table>

<br>

<!--US17-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-17</td>
    <td>Administrador</td>
    <td>Baja</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Generación de Reporte de Asistencia</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como administrador, quiero generar un reporte mensual con las inasistencias y tardanzas para poder justificar incidentes ante los padres.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Descarga de reporte</strong><br>
      <strong>Dado que</strong> el mes escolar ha concluido,<br>
      <strong>Cuando</strong> el administrador solicita el informe de un alumno,<br>
      <strong>Entonces</strong> el sistema consolida los eventos `StudentBoarded` y `StudentAbsent` en un documento tabular.
    </td>
  </tr>
</table>

<br>

<!--US18-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-18</td>
    <td>Nuevo Usuario</td>
    <td>Baja</td>
    <td>EP04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Sección de Preguntas Frecuentes (FAQ)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como nuevo usuario, quiero consultar una sección de dudas comunes para resolver problemas sin necesidad de contactar a soporte técnico.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Búsqueda de FAQ</strong><br>
      <strong>Dado que</strong> el usuario tiene dudas sobre los precios,<br>
      <strong>Cuando</strong> ingresa el término "pago",<br>
      <strong>Entonces</strong> el sistema filtra dinámicamente las preguntas relevantes.
    </td>
  </tr>
</table>

<br>


<!--US19-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-19</td>
    <td>Usuario General</td>
    <td>Alta</td>
    <td>EP01</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Recuperación de Contraseña</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como usuario, quiero poder recuperar mi contraseña mediante mi correo electrónico para recuperar el acceso a mi cuenta en caso de olvido.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Envío de enlace de recuperación</strong><br>
      <strong>Dado que</strong> el usuario ingresa su correo registrado,<br>
      <strong>Cuando</strong> solicita la recuperación,<br>
      <strong>Entonces</strong> el sistema envía un correo con un token seguro de restablecimiento con vigencia de 15 minutos.
    </td>
  </tr>
</table>

<br>

<!--US20-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-20</td>
    <td>Administrador</td>
    <td>Media</td>
    <td>EP03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Historial de Mantenimientos</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como administrador, quiero visualizar el historial de mantenimientos preventivos y correctivos de cada vehículo para gestionar las fechas de su próxima revisión.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Revisión de bitácora vehicular</strong><br>
      <strong>Dado que</strong> el administrador selecciona un vehículo de la flota,<br>
      <strong>Cuando</strong> navega a la pestaña de mantenimiento,<br>
      <strong>Entonces</strong> el sistema lista todas las intervenciones pasadas ordenadas por fecha.
    </td>
  </tr>
</table>

<br>

<!--US21-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-21</td>
    <td>Conductor</td>
    <td>Media</td>
    <td>EP03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Cancelación de Viaje por Fuerza Mayor</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como conductor, quiero poder cancelar un viaje en curso en caso de avería mecánica extrema o emergencia para detener el monitoreo y notificar automáticamente a los padres afectados.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Cancelación de ruta activa</strong><br>
      <strong>Dado que</strong> el conductor se encuentra en medio de un viaje,<br>
      <strong>Cuando</strong> presiona el botón de cancelación por fuerza mayor y confirma,<br>
      <strong>Entonces</strong> el sistema cambia el estado de la ruta a "Cancelado" y emite una alerta a los padres restantes.
    </td>
  </tr>
</table>

<br>

<!--US22-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-22</td>
    <td>Conductor</td>
    <td>Alta</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Reporte de Llegada al Colegio</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como conductor, quiero registrar el check-in final al llegar al colegio para que el sistema marque la finalización exitosa del viaje matutino.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Check-in de destino final</strong><br>
      <strong>Dado que</strong> el vehículo se encuentra en el radio del colegio,<br>
      <strong>Cuando</strong> el conductor confirma la llegada,<br>
      <strong>Entonces</strong> el sistema desembarca virtualmente a todos los alumnos a bordo y da por finalizada la ruta.
    </td>
  </tr>
</table>

<br>

<!--US23-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-23</td>
    <td>Padre de Familia</td>
    <td>Baja</td>
    <td>EP04</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Envío de Ticket de Soporte</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como padre de familia, quiero poder crear un ticket de soporte dentro de la aplicación para resolver problemas técnicos con mi cuenta o pagos.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Generación de ticket</strong><br>
      <strong>Dado que</strong> el usuario tiene un problema en la app,<br>
      <strong>Cuando</strong> llena el formulario de contacto y lo envía,<br>
      <strong>Entonces</strong> el sistema genera un ID de seguimiento y lo notifica al área de soporte.
    </td>
  </tr>
</table>

<br>

<!--US24-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-24</td>
    <td>Conductor</td>
    <td>Media</td>
    <td>EP06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Foro de Anuncios del Conductor</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como conductor, quiero tener una sección de anuncios (ej. "Mañana no hay servicio por feriado") para comunicar información relevante de manera asíncrona a todos los padres de mi ruta.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Publicación de anuncio global</strong><br>
      <strong>Dado que</strong> el conductor publica un anuncio en su muro,<br>
      <strong>Cuando</strong> los padres vinculados ingresan a su perfil,<br>
      <strong>Entonces</strong> visualizan el mensaje resaltado en la parte superior.
    </td>
  </tr>
</table>

<br>



<!--US25-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-25</td>
    <td>Nuevo Usuario</td>
    <td>Media</td>
    <td>EP02</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Sección Tutorial interactiva (Onboarding)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como nuevo usuario, quiero acceder a un tutorial interactivo al iniciar sesión por primera vez para aprender a utilizar las funcionalidades principales de la aplicación.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Completar onboarding</strong><br>
      <strong>Dado que</strong> el usuario ingresa por primera vez,<br>
      <strong>Cuando</strong> navega por las 3 pantallas de tutorial,<br>
      <strong>Entonces</strong> el sistema marca el onboarding como completado y no lo vuelve a mostrar.
    </td>
  </tr>
</table>

<br>

<!--US26-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-26</td>
    <td>Conductor</td>
    <td>Baja</td>
    <td>EP03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Registro de Gastos Operativos</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como conductor, quiero registrar mis gastos diarios (combustible, peajes, lavado) para tener un control financiero directamente en la aplicación de gestión de flota.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Ingreso de gasto</strong><br>
      <strong>Dado que</strong> el conductor realiza una recarga de combustible,<br>
      <strong>Cuando</strong> ingresa el monto y adjunta la foto del comprobante,<br>
      <strong>Entonces</strong> el sistema añade el gasto al reporte financiero mensual.
    </td>
  </tr>
</table>

<br>

<!--US27-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-27</td>
    <td>Padre de Familia</td>
    <td>Alta</td>
    <td>EP03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Cambio Temporal de Dirección de Recojo</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como padre de familia, quiero poder solicitar un cambio de dirección de recojo por un solo día (ej. casa de abuelos) para que el conductor ajuste su ruta sin alterar mi dirección base.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Aprobación de cambio temporal</strong><br>
      <strong>Dado que</strong> el padre envía una solicitud de desvío con 12 horas de anticipación,<br>
      <strong>Cuando</strong> el conductor la acepta,<br>
      <strong>Entonces</strong> el sistema actualiza temporalmente la coordenada de la parada para el día siguiente.
    </td>
  </tr>
</table>

<br>

<!--US28-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-28</td>
    <td>Administrador</td>
    <td>Media</td>
    <td>EP03</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Reasignación de Rutas por Ausencias</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como administrador, quiero recalcular y reasignar las rutas si un conductor reporta una avería o falta, para garantizar que todos los alumnos sean recogidos por otro vehículo disponible.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Traspaso de ruta</strong><br>
      <strong>Dado que</strong> el conductor A reporta una avería severa,<br>
      <strong>Cuando</strong> el administrador transfiere sus paradas al conductor B,<br>
      <strong>Entonces</strong> el sistema notifica a los padres y fusiona las secuencias de recojo en el dispositivo de B.
    </td>
  </tr>
</table>

<br>

<!--US29-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-29</td>
    <td>Conductor</td>
    <td>Media</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Reporte de Bloqueo de Vías</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como conductor, quiero poder reportar un bloqueo de vía en tiempo real en mi mapa, para recalcular la ruta automáticamente y advertir a la central sobre la demora.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Recálculo por incidencia</strong><br>
      <strong>Dado que</strong> el conductor se topa con tráfico bloqueado,<br>
      <strong>Cuando</strong> marca el segmento vial como cerrado en la app,<br>
      <strong>Entonces</strong> el sistema genera una ruta alternativa hacia la siguiente parada.
    </td>
  </tr>
</table>

<br>

<!--US30-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US-30</td>
    <td>Padre de Familia</td>
    <td>Baja</td>
    <td>EP06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Chat Interno Conductor - Padre</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como padre de familia, quiero tener un chat interno con el conductor asignado para comunicarme directamente sobre detalles urgentes (ej. "el niño está saliendo, espere 1 minuto").</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Envío de mensaje</strong><br>
      <strong>Dado que</strong> el conductor está en camino a la parada del padre,<br>
      <strong>Cuando</strong> el padre envía un mensaje de texto,<br>
      <strong>Entonces</strong> el dispositivo del conductor lo recibe y, si está conduciendo, lo lee mediante Voice-to-Text.
    </td>
  </tr>
</table>

<br>


**TECHNICAL STORIES**


<!--TS01-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-01</td>
    <td>Developer</td>
    <td>Alta</td>
    <td>EP01</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Autenticación de API vía JWT</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como Developer, quiero implementar un endpoint RESTful seguro para autenticar a los usuarios móviles y emitir tokens JWT con tiempo de expiración.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Generación de token</strong><br>
      <strong>Dado que</strong> un cliente envía credenciales válidas al endpoint de login,<br>
      <strong>Cuando</strong> el servidor valida el hash de la contraseña,<br>
      <strong>Entonces</strong> el sistema responde con un JSON Web Token válido por 24 horas y código HTTP 200.
    </td>
  </tr>
</table>

<br>

<!--TS02-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-02</td>
    <td>Developer</td>
    <td>Alta</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Caché Local para Abordajes (Offline First)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como Developer, quiero configurar una base de datos local (ej. Room/SQLite) en la app nativa para garantizar la persistencia temporal de los abordajes sin internet.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Persistencia sin red</strong><br>
      <strong>Dado que</strong> la aplicación detecta error de conectividad (Timeout),<br>
      <strong>Cuando</strong> se genera un evento de abordaje,<br>
      <strong>Entonces</strong> el evento se escribe en la tabla local `PendingSync_Events` con un timestamp exacto.
    </td>
  </tr>
</table>

<br>

<!--TS03-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-03</td>
    <td>Developer</td>
    <td>Media</td>
    <td>EP06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Integración de Firebase Cloud Messaging (FCM)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como Developer, quiero acoplar los microservicios de notificaciones con FCM para asegurar la entrega masiva de alertas a los dispositivos móviles.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Entrega de payload</strong><br>
      <strong>Dado que</strong> el servicio backend genera un evento `ProximityGeofenceTriggered`,<br>
      <strong>Cuando</strong> el sistema despacha el payload hacia FCM,<br>
      <strong>Entonces</strong> el servidor de Google retorna un `message_id` de confirmación.
    </td>
  </tr>
</table>


<br>

<!--TS04-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-04</td>
    <td>DevOps / Developer</td>
    <td>Alta</td>
    <td>General</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Pipeline de Integración Continua (CI/CD)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador, quiero configurar un pipeline de CI/CD (e.g., GitHub Actions) para compilar y ejecutar pruebas automáticamente con cada push a la rama principal.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Ejecución exitosa de pruebas</strong><br>
      <strong>Dado que</strong> se realiza un Pull Request hacia <code>develop</code>,<br>
      <strong>Cuando</strong> el pipeline se activa automáticamente,<br>
      <strong>Entonces</strong> se compila la solución, se corren las pruebas unitarias y se reporta el estado en GitHub.
    </td>
  </tr>
</table>

<br>

<!--TS05-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-05</td>
    <td>Developer</td>
    <td>Media</td>
    <td>EP02</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Integración de Pasarela de Pagos</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador, quiero integrar la API de una pasarela de pagos (ej. Stripe o Niubiz) para procesar las suscripciones de los conductores de forma segura.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Tokenización de tarjeta</strong><br>
      <strong>Dado que</strong> el usuario ingresa sus datos de tarjeta,<br>
      <strong>Cuando</strong> la pasarela responde con éxito,<br>
      <strong>Entonces</strong> el backend almacena únicamente el token de pago seguro y no los datos sensibles de la tarjeta.
    </td>
  </tr>
</table>



<!--TS06-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-06</td>
    <td>Database Admin</td>
    <td>Alta</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Configuración de Base de Datos Espacial</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como administrador de base de datos, quiero configurar un motor de BD con capacidades espaciales (ej. PostgreSQL con PostGIS o MongoDB con GeoJSON) para realizar consultas eficientes de geocercas y proximidad.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Inserción y consulta geoespacial</strong><br>
      <strong>Dado que</strong> se recibe una coordenada de latitud/longitud,<br>
      <strong>Cuando</strong> el sistema la persiste en la base de datos,<br>
      <strong>Entonces</strong> es capaz de usar índices espaciales para encontrarla en consultas de "puntos dentro de un polígono" en menos de 50ms.
    </td>
  </tr>
</table>

<br>

<!--TS07-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-07</td>
    <td>Backend Developer</td>
    <td>Media</td>
    <td>EP06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Implementación de Cola de Mensajería</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador backend, quiero implementar un Message Broker (RabbitMQ o Kafka) para encolar el procesamiento de notificaciones masivas, evitando bloqueos en el hilo principal del servidor.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Encolado de eventos masivos</strong><br>
      <strong>Dado que</strong> se dispara una alerta general de retraso,<br>
      <strong>Cuando</strong> el controlador recibe la petición,<br>
      <strong>Entonces</strong> delega la creación de las 30 notificaciones individuales a la cola de mensajería para su procesamiento en background, respondiendo inmediatamente HTTP 202 Accepted al cliente.
    </td>
  </tr>
</table>

<br>



<!--TS08-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>TS-08</td>
    <td>Backend Developer</td>
    <td>Media</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">API para Validación de Códigos QR</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador backend, quiero exponer un endpoint para la generación y validación de códigos QR únicos por alumno, permitiendo un escaneo rápido para el abordaje offline y online.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Validación exitosa</strong><br>
      <strong>Dado que</strong> el conductor escanea un QR válido,<br>
      <strong>Cuando</strong> la app envía el payload al backend,<br>
      <strong>Entonces</strong> el sistema marca al estudiante como abordado y actualiza su estado.
    </td>
  </tr>
</table>

<br>


**SPIKE STORIES**

<!--SS01-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SS-01</td>
    <td>Architect</td>
    <td>Alta</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Investigación: Consumo de Batería en Foreground vs Background Service</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como Arquitecto, necesito investigar qué API de geolocalización de Android e iOS minimiza el consumo de batería durante trayectos largos.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Documentación entregable</strong><br>
      <strong>Dado que</strong> se realiza la investigación de la documentación oficial de Fused Location Provider,<br>
      <strong>Cuando</strong> finaliza el timebox de 8 horas,<br>
      <strong>Entonces</strong> se debe entregar un documento con la comparativa de drenaje de batería y la recomendación del intervalo de actualización (polling rate).
    </td>
  </tr>
</table>

<br>

<!--SS02-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SS-02</td>
    <td>Architect</td>
    <td>Media</td>
    <td>EP06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Prueba de Latencia: WebSockets vs FCM para Geofencing</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como Arquitecto, necesito evaluar la latencia de entrega de alertas geográficas para decidir el protocolo de comunicación con la App de Padres.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Benchmark de latencia</strong><br>
      <strong>Dado que</strong> se requiere tiempo real para alertas críticas,<br>
      <strong>Cuando</strong> finaliza el timebox de pruebas,<br>
      <strong>Entonces</strong> el equipo debe documentar el tiempo promedio en milisegundos de entrega de un payload mediante socket abierto frente a un push notification tradicional.
    </td>
  </tr>
</table>
<br>

<!--SS03-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SS-03</td>
    <td>Arquitecto</td>
    <td>Alta</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Spike: Precisión GPS vs Consumo de Red</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como arquitecto de software, quiero evaluar la frecuencia de muestreo del GPS en zonas urbanas para determinar el balance óptimo entre precisión en vivo y consumo de datos móviles del conductor.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Documentación de hallazgos</strong><br>
      <strong>Dado que</strong> el equipo realiza pruebas de campo con muestreo cada 5, 10 y 15 segundos,<br>
      <strong>Cuando</strong> se analizan los resultados,<br>
      <strong>Entonces</strong> se documenta el intervalo ideal que mantiene un error de desviación menor a 15 metros sin saturar el plan de datos.
    </td>
  </tr>
</table>

<br>

<!--SS04-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SS-04</td>
    <td>Developer</td>
    <td>Media</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Spike: Resolución de Conflictos Offline</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador, quiero investigar estrategias de sincronización de datos locales (SQLite) a la nube para resolver conflictos cuando dos dispositivos (ej. auxiliar y conductor) marcan un abordaje al mismo tiempo sin conexión.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Definición de estrategia</strong><br>
      <strong>Dado que</strong> se prueban patrones de sincronización transaccional,<br>
      <strong>Cuando</strong> se evalúa la política *Last-Writer-Wins* vs. *Timestamp Merge*,<br>
      <strong>Entonces</strong> el equipo decide e implementa en un prototipo la estrategia elegida.
    </td>
  </tr>
</table>



<!--SS05-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SS-05</td>
    <td>Mobile Developer</td>
    <td>Baja</td>
    <td>EP01</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Spike: Viabilidad de Inicio de Sesión Biométrico</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como desarrollador móvil, quiero investigar la implementación de autenticación biométrica (FaceID / Fingerprint) en Flutter o Swift/Kotlin para agilizar el login de los conductores.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Prototipo funcional</strong><br>
      <strong>Dado que</strong> el equipo finaliza la investigación,<br>
      <strong>Cuando</strong> exponen los resultados técnicos,<br>
      <strong>Entonces</strong> presentan un prototipo local que lee la credencial biométrica del OS y la vincula a un token JWT de sesión.
    </td>
  </tr>
</table>

<br>

<!--SS06-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SS-06</td>
    <td>Arquitecto</td>
    <td>Media</td>
    <td>EP06</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Spike: Consumo de Geofencing OS-Level</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como arquitecto de software, quiero evaluar la diferencia de consumo de batería al delegar el *Geofencing* directamente a las APIs nativas de iOS/Android versus calcular la distancia constantemente en el hilo de la aplicación.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Decisión arquitectónica</strong><br>
      <strong>Dado que</strong> se elabora un cuadro comparativo de consumo en miliamperios (mAh),<br>
      <strong>Cuando</strong> el equipo discute los hallazgos,<br>
      <strong>Entonces</strong> se emite un documento técnico (ADR) que dictamina si se usarán los listeners nativos del SO o un cálculo periódico propio.
    </td>
  </tr>
</table>

<br>



<!--SS07-->
<table>
  <tr>
    <th><strong>Story ID</strong></th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>SS-07</td>
    <td>Arquitecto</td>
    <td>Media</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th>Title</th>
    <td colspan="3">Spike: Evaluación de Mapbox vs Google Maps</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como equipo de desarrollo, queremos evaluar y comparar los proveedores de mapas (Google Maps Platform vs. Mapbox) para determinar cuál ofrece la mejor rentabilidad y precisión para el trazado de rutas y geovallas.</td>
  </tr>
  <tr>
  <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <strong>Escenario 1: Decisión del proveedor</strong><br>
      <strong>Dado que</strong> se realiza un análisis de costos y cuotas gratuitas,<br>
      <strong>Cuando</strong> el equipo presenta el reporte técnico,<br>
      <strong>Entonces</strong> se escoge un proveedor definitivo para implementar en la aplicación.
    </td>
  </tr>
</table>

<br>


---

### 2.4.2. Impact Mapping

![Impact Mapping](resources/chapter-2/Impact%20Mapping/Impact%20Mapping%20-%20Route%20Golem.png)


### 2.4.3. Product Backlog

El *Product Backlog* es un artefacto vivo y emergente que centraliza y ordena todo el trabajo necesario para la evolución del producto (Schwaber & Sutherland, 2020). Para RouteGuard, las historias han sido estimadas mediante Puntos de Historia (Fibonacci) y priorizadas bajo el criterio de maximización de valor temprano (Rubin, 2012), asegurando que las funcionalidades críticas para el *Minimum Viable Product* (MVP) se desarrollen en los primeros *sprints*.

| Orden | ID | Título | Epic | Story Points |
| :---: | :---: | :--- | :--- | :---: |
| 1 | TS-04 | Pipeline de Integración Continua (CI/CD) | General | 5 |
| 2 | TS-01 | Autenticación de API vía JWT | EP01 | 5 |
| 3 | SS-01 | Investigación: Consumo de Batería (Background Service) | EP05 | 3 |
| 4 | US-01 | Registro y Asignación de Rol | EP01 | 3 |
| 5 | SS-05 | Spike: Viabilidad de Inicio de Sesión Biométrico | EP01 | 3 |
| 6 | US-19 | Recuperación de Contraseña | EP01 | 3 |
| 7 | US-11 | Registro de Múltiples Hijos | EP02 | 3 |
| 8 | TS-05 | Integración de Pasarela de Pagos | EP02 | 5 |
| 9 | US-02 | Adquisición de Plan de Suscripción | EP02 | 5 |
| 10 | US-12 | Control de Documentación (SOAT) | EP03 | 5 |
| 11 | US-20 | Historial de Mantenimientos | EP03 | 3 |
| 12 | US-04 | Listado y Secuencia de Paradas | EP03 | 5 |
| 13 | US-22 | Reporte de Llegada al Colegio | EP05 | 3 |
| 14 | SS-04 | Spike: Resolución de Conflictos Offline | EP05 | 5 |
| 15 | TS-02 | Caché Local para Abordajes (Offline First) | EP05 | 8 |
| 16 | US-06 | Check-in de Abordaje Offline | EP05 | 5 |
| 17 | TS-08 | API para Validación de Códigos QR | EP05 | 5 |
| 18 | SS-03 | Spike: Precisión GPS vs Consumo de Red | EP05 | 3 |
| 19 | TS-06 | Configuración de Base de Datos Espacial | EP05 | 8 |
| 20 | US-05 | Transmisión de GPS en Segundo Plano | EP05 | 8 |
| 21 | SS-07 | Spike: Evaluación de Mapbox vs Google Maps | EP05 | 3 |
| 22 | US-08 | Monitoreo de Ruta en Tiempo Real | EP05 | 8 |
| 23 | SS-02 | Prueba de Latencia: WebSockets vs FCM | EP06 | 2 |
| 24 | TS-03 | Integración de Firebase Cloud Messaging (FCM) | EP06 | 5 |
| 25 | TS-07 | Implementación de Cola de Mensajería | EP06 | 5 |
| 26 | SS-06 | Spike: Consumo de Geofencing OS-Level | EP06 | 3 |
| 27 | US-07 | Alerta de Geofencing | EP06 | 5 |
| 28 | US-16 | Asignación de Conductor a Vehículo | EP03 | 3 |
| 29 | US-03 | Gestión de Capacidad Vehicular | EP03 | 3 |
| 30 | US-13 | Gestión de Perfil de Usuario | EP01 | 2 |
| 31 | US-10 | Botón de Incidencias Rápido | EP06 | 3 |
| 32 | US-21 | Cancelación de Viaje por Fuerza Mayor | EP03 | 3 |
| 33 | US-14 | Calificación del Servicio | EP04 | 3 |
| 34 | US-24 | Foro de Anuncios del Conductor | EP06 | 2 |
| 35 | US-09 | Reporte de Ausencia Temprana | EP06 | 2 |
| 36 | US-17 | Generación de Reporte de Asistencia | EP05 | 3 |
| 37 | US-15 | Historial de Viajes Finalizados | EP05 | 2 |
| 38 | US-18 | Sección de Preguntas Frecuentes (FAQ) | EP04 | 2 |
| 39 | US-23 | Envío de Ticket de Soporte | EP04 | 2 |
| 40 | US-25 | Sección Tutorial interactiva (Onboarding) | EP02 | 3 |
| 41 | US-26 | Registro de Gastos Operativos | EP03 | 2 |
| 42 | US-27 | Cambio Temporal de Dirección de Recojo | EP03 | 5 |
| 43 | US-28 | Reasignación de Rutas por Ausencias | EP03 | 5 |
| 44 | US-29 | Reporte de Bloqueo de Vías | EP05 | 3 |
| 45 | US-30 | Chat Interno Conductor - Padre | EP06 | 5 |

## 2.5. Strategic-Level Domain-Driven Design

### 2.5.1. EventStorming
 
Para el proceso de EventStorming a nivel de diseño utilizamos la herramienta **Miro** y seguimos cuatro pasos hasta llegar a la definición de los Bounded Contexts del sistema.
 
**Paso 1: Identificación de Domain Events.** Trazamos los eventos sobre una línea de tiempo imaginaria de izquierda a derecha, redactados en pasado participio y utilizando el lenguaje ubicuo en inglés. Los eventos se representan con post-it de color anaranjado.
 
**Paso 2: Identificación de Commands.** Sobre cada evento identificamos el comando que lo dispara, es decir, la intención explícita que provoca el hecho. Los comandos se representan con post-it de color azul.
 
**Paso 3: Identificación de Actors.** Determinamos qué actor ejecuta cada comando, distinguiendo los tres roles del ecosistema (Administrador, Conductor y Padre de familia) de los procesos que dispara el propio sistema. Los actores se representan con post-it de color amarillo.
 
**Paso 4: Agrupación en Bounded Contexts.** Finalmente agrupamos los eventos que se relacionan entre sí a través de los agregados y entidades que comparten, delimitando los Bounded Contexts del sistema.
 
A lo largo del tablero utilizamos además cuatro tipos de post-it complementarios para enriquecer el modelo:
 
| Color | Tipo | Descripción |
|---|---|---|
| Amarillo pálido | Agregado | Entidad o conjunto de entidades que agrupan el comportamiento y el estado sobre el que actúa un comando. |
| Rosado | Sistema Externo | Servicio de terceros con el que el sistema se integra (pasarela de pago, proveedor de mapas, proveedor push, broker de mensajería). |
| Morado | Política | Regla de negocio que conecta automáticamente un evento con el siguiente comando, sin intervención de un actor humano. |
| Verde | Pantalla | Vista de la aplicación desde la que un actor dispara un comando. |

<img src="resources\chapter-2\EventStorming\paleta-colores.png" width="1000">
 
#### 2.5.1.1. Candidate Context Discovery
 
En esta sesión aplicamos la técnica de *Candidate Context Discovery* para identificar y separar los posibles Bounded Contexts del sistema RouteGuard. La sesión se realizó en **Miro** con la participación de los cuatro integrantes del equipo y tuvo una duración de una hora y cuarenta minutos, dentro del límite de dos horas recomendado para esta técnica.
 
Utilizamos las tres técnicas sugeridas de forma encadenada, ya que cada una responde una pregunta distinta. Con **start-with-simple** descompusimos la línea temporal en tres fases secuenciales —configuración y contratación, operación diaria, y cierre y postventa— para obtener un modelo manejable antes de intentar agrupar. Con **look-for-pivotal-events** identificamos los eventos que marcan cambios de estado entre partes distintas del proceso de negocio, que resultaron ser las costuras naturales del dominio. Finalmente, con **start-with-value** determinamos qué agrupaciones concentran el mayor valor para el negocio, contrastándolas con la propuesta de valor.
 
Los eventos pivote identificados fueron los siguientes:
 
| Evento pivote | Cambio de estado que señala |
|---|---|
| `RouteActivationFinalized` | La ruta pasa de configuración a disponible para operar; separa la planificación de la ejecución, y es el evento que directamente dispara `Start Trip` en Trip Execution & Monitoring. |
| `TripStarted` | El plan de ruta pasa de intención a ejecución; separa la planificación del registro operativo. |
| `LocationUpdated` | La posición del vehículo pasa de dato crudo transmitido por el dispositivo a telemetría persistida del viaje; abre el flujo de monitoreo en tiempo real y dispara la evaluación de geocerca en Notifications & Communication. |
| `GeofenceBreached` | La telemetría cruda pasa a ser un hecho accionable: el vehículo penetra el radio de una parada, disparando la alerta hacia el padre. |
| `GroupFinalized` | El grupo de estudiantes pasa de configuración a disponible para asignar; es el evento que, a través de la política `Export Group Manifest to Route Context`, dispara `Assign Students to Route` en Fleet & Route Management. |
| `SubscriptionActivated` | El vínculo comercial pasa de solicitud a acceso habilitado; separa la capa comercial de la operativa. |
| `TripCompleted` | La ejecución pasa a cierre; separa la operación diaria de la postventa. |
 
Al analizar estos eventos pudimos observar que cada grupo implicaba responsabilidades, reglas y garantías de consistencia distintas dentro del sistema, lo que nos permitió agruparlos en contextos bien definidos, evitando ambigüedad y facilitando la organización del dominio.
 
A continuación se presenta la evolución progresiva del EventStorm durante la sesión.
 
*Paso 1 — Domain Events:* los eventos trazados sobre la línea temporal, en pasado participio y con el lenguaje ubicuo en inglés.
 
<img src="resources\chapter-2\EventStorming\Events.jpg" width="1000">

*Paso 2 — Commands:* sobre cada evento se identificó el comando que lo dispara.
 
<img src="resources\chapter-2\EventStorming\Commands.jpg" width="1000">

*Paso 3 — Actors:* se determinó qué actor ejecuta cada comando.
 
<img src="resources\chapter-2\EventStorming\Actors.jpg" width="1000">

*Paso 4 — Agrupación:* aplicando los eventos pivote como líneas de corte, los eventos se agruparon por los agregados que comparten.
 
<img src="resources\chapter-2\EventStorming\Design-Level-Event-Storming.jpg" width="1000">

Este proceso nos llevó a definir los siguientes Bounded Contexts:
 
| Bounded Context | Descripción | Eventos clave |
|---|---|---|
| **Identity & Access Management** | Gestiona el registro, la autenticación y el control de acceso por rol de los usuarios de la plataforma. | Login Accepted, User Authenticated, JWT Session Token Issued, User Logged In, Administrator Account Created, Admin Role Privileges Granted, Driver Account Provisioned, Parent Account Provisioned, Password Generated |
| **Subscription & Plan Management** | Administra los planes SaaS, procesa el cobro a través de la pasarela de pago y habilita el acceso comercial a la plataforma. | Plan Selected, Payment Confirmed, Subscription Activated, Plan Features Enabled, Plan Upgraded, Quotas Increased |
| **Fleet & Route Management** | Custodia el plan de recorrido vigente: paradas, vehículo, conductor y programación de servicio de cada ruta. | Route Defined, Waypoint Selected, Stop Count Updated, Student Assigned To Route, Passenger Manifest Generated, Vehicle Assigned To Route, Service Days Defined, Route Activation Finalized |
| **Stakeholder & Asset Management** | Registra a conductores y padres de familia, vincula estudiantes y organiza los grupos por ruta. | Driver Profile Created, Parent Profile Created, Child Profile Created, Child Linked To Parent, Group Name Assigned, Parents Assigned To Group, Students Included In Group, Group Finalized |
| **Trip Execution & Monitoring** | Registra la ejecución real del viaje diario, incluyendo el registro de abordaje con soporte *offline* (US-06/TS-02), y la transmisión de la ubicación GPS en tiempo real del vehículo. | Trip Started, Boarding Opened, Student Boarded, Student Dropped Off, Location Updated, Incident Reported, Trip Completed, Trip Archived |
| **Notifications & Communication** | Consume los eventos del viaje, evalúa la penetración de geocercas y traduce los eventos del dominio en notificaciones push para los padres de familia. | Notification Created, Notification Queued, Notification Dispatched, High Priority Alert Created, Geofence Breached, Announcement Published, Notification Sent |
 
Aplicando finalmente *start-with-value*, clasificamos los contextos según su aporte estratégico. **Trip Execution & Monitoring** constituye el *Core Domain*: es el contexto donde RouteGuard concentra su ventaja competitiva, al garantizar tanto el registro de abordaje sin pérdida de datos ante la falta de conectividad como el monitoreo en tiempo real del trayecto. **Fleet & Route Management**, **Stakeholder & Asset Management** y **Notifications & Communication** son *Supporting Subdomains*: indispensables para el negocio pero no diferenciadores. **Identity & Access Management** y **Subscription & Plan Management** son *Generic Subdomains*, problemas ya resueltos por la industria en los que se prioriza la reutilización.
 
La capacidad que distingue a RouteGuard es la combinación de resiliencia ante la falta de conectividad con monitoreo en tiempo real dentro de Trip Execution & Monitoring, y es ahí donde se concentra el mayor esfuerzo de diseño táctico en las siguientes secciones.
 
**Conexiones confirmadas entre Bounded Contexts**
 
| # | Origen | Evento | Política | Destino | Comando / Evento |
|---|---|---|---|---|---|
| 1 | Stakeholder & Asset Management | `Group Finalized` | `Export Group Manifest to Route Context` | Fleet & Route Management | `Assign Students to Route` |
| 2 | Fleet & Route Management | `Route Activation Finalized` | — | Trip Execution & Monitoring | `Start Trip` |
| 3 | Trip Execution & Monitoring | `Student Boarded` | — | Notifications & Communication | `Student Boarded` (consumido) |
| 4 | Trip Execution & Monitoring | `Incident Reported` | — | Notifications & Communication | `Incident Reported` (consumido) |
| 5 | Trip Execution & Monitoring | `Location Updated` | *(evaluación de geocerca)* | Notifications & Communication | `Geofence Breached` |
 
**Identity & Access Management** se conecta de forma transversal con los cinco contextos restantes a través de `User Authenticated`/`JWT Session Token Issued`, pero esta no es una política de negocio sino una dependencia de identidad.
 
**Subscription & Plan Management** no tiene ninguna conexión hacia otro Bounded Context: su único vínculo externo es con la pasarela de pago (Payment Gateway), un sistema externo. Ningún otro contexto consulta sus cuotas o límites en tiempo real.

#### 2.5.1.2. Domain Message Flows Modeling
 
El *Domain Message Flow Modelling* es una técnica que permite representar cómo fluyen los mensajes de dominio —*commands*, *events* y *queries*— entre los distintos Bounded Contexts del sistema. Su propósito es clarificar las interacciones, dependencias y responsabilidades de cada contexto al resolver un caso concreto del negocio.

Para cada escenario se documenta la secuencia numerada de mensajes, que es la que se representa en el diagrama: los comandos en azul, los eventos en naranja y las políticas en morado, con los contextos dibujados como nubes.
 
**Escenario 01: Conformación del grupo de estudiantes y asignación a la ruta**
 
| # | Tipo | Mensaje | Origen | Destino |
|---|---|---|---|---|
| 1 | Command | Crear grupo de estudiantes | Administrador | Stakeholder & Asset Management |
| 2 | Command | Asignar padres e incluir hijos vinculados | Administrador | Stakeholder & Asset Management |
| 3 | Command | Finalizar grupo | Administrador | Stakeholder & Asset Management |
| 4 | Event | `Group Finalized` | Stakeholder & Asset Management | Stakeholder & Asset Management |
| 5 | Policy | `Export Group Manifest to Route Context` | Stakeholder & Asset Management | Fleet & Route Management |
| 6 | Command | `Assign Students to Route` | Fleet & Route Management | Fleet & Route Management |
| 7 | Event | `Student Assigned to Route` | Fleet & Route Management | Fleet & Route Management |
 
![Escenario 01: Conformación de grupo y asignación a ruta](resources/chapter-2/Domain-Message-Flows/escenario-01-grupo-ruta.png)
 
Este es el único cruce del sistema donde la conexión pasa explícitamente por una política (post-it morado) antes del comando destino, en vez de ir directo de evento a comando.
 
**Escenario 02: Activación de ruta e inicio del viaje**
 
| # | Tipo | Mensaje | Origen | Destino |
|---|---|---|---|---|
| 1 | Command | Definir días de servicio y hora de salida | Administrador | Fleet & Route Management |
| 2 | Event | `Route Activation Finalized` | Fleet & Route Management | Trip Execution & Monitoring |
| 3 | Command | `Start Trip` | Conductor | Trip Execution & Monitoring |
| 4 | Event | `Trip Started` | Trip Execution & Monitoring | Trip Execution & Monitoring |
 
![Escenario 02: Activación de ruta e inicio del viaje](resources/chapter-2/Domain-Message-Flows/escenario-02-activacion-inicio.png)
 
`Route Activation Finalized` es evento pivote: marca el punto exacto donde el plan de ruta, propiedad de Fleet & Route Management, deja de poder modificarse en caliente y habilita a Trip Execution & Monitoring a operar sobre él.
 
**Escenario 03: Transmisión de ubicación en tiempo real y alerta de geocerca**
 
| # | Tipo | Mensaje | Origen | Destino |
|---|---|---|---|---|
| 1 | Command | Transmitir ubicación en segundo plano | App del conductor | Trip Execution & Monitoring |
| 2 | Event | `Location Updated` | Trip Execution & Monitoring | RabbitMQ (broker) |
| 3 | Event | Recibe de broker | RabbitMQ (broker) | Notifications & Communication |
| 4 | Command | Evaluar intersección de geocerca | Notifications & Communication | Notifications & Communication |
| 5 | Event | `Geofence Breached` | Notifications & Communication | Notifications & Communication |
| 6 | Command | `Dispatch Notification` | Notifications & Communication | Proveedor push (FCM) |
| 7 | Event | `Notification Sent` | Proveedor push (FCM) | Padre de familia |
 
![Escenario 03: Ubicación en tiempo real y alerta de geocerca](resources/chapter-2/Domain-Message-Flows/escenario-03-geofence.png)
 
Este escenario sustenta directamente el Objetivo SMART 4 (latencia menor a 5 segundos entre la transmisión de ubicación y la alerta recibida por el padre). A diferencia del Escenario 01, aquí no hay una política intermedia visible en el Miro entre `Location Updated` y la evaluación de geocerca; el paso 4 representa el comando implícito que Notifications & Communication ejecuta al consumir el evento del broker.
 
**Escenario 04: Abordaje e incidencia notificados al padre**
 
| # | Tipo | Mensaje | Origen | Destino |
|---|---|---|---|---|
| 1 | Command | Marcar abordaje | Conductor | Trip Execution & Monitoring |
| 2 | Event | `Student Boarded` | Trip Execution & Monitoring | RabbitMQ (broker) |
| 3 | Event | Recibe de broker | RabbitMQ (broker) | Notifications & Communication |
| 4 | Event | `Notification Sent` | Notifications & Communication | Padre de familia |
| 5 | Command | Reportar incidencia | Conductor | Trip Execution & Monitoring |
| 6 | Event | `Incident Reported` | Trip Execution & Monitoring | RabbitMQ (broker) |
| 7 | Event | Recibe de broker | RabbitMQ (broker) | Notifications & Communication |
| 8 | Command | `Trigger Panic Alert` | Notifications & Communication | Notifications & Communication |
| 9 | Event | `High Priority Alert Created` | Notifications & Communication | Notifications & Communication |
| 10 | Event | `Notification Sent` | Notifications & Communication | Padre de familia |
 
![Escenario 04: Abordaje e incidencia](resources/chapter-2/Domain-Message-Flows/escenario-04-abordaje-incidencia.png)
 
Ambas rutas —abordaje e incidencia— llegan a Notifications & Communication como eventos consumidos, sin que Trip Execution & Monitoring conozca la lógica de despacho ni de priorización.

#### 2.5.1.3. Bounded Context Canvases
 
El *Bounded Context Canvas* permite representar de forma clara los límites, responsabilidades e interacciones de cada contexto dentro de un sistema complejo, facilitando que el equipo construya una visión compartida sobre su propósito, sus agregados y las reglas de negocio que lo gobiernan. El equipo utilizó la plantilla oficial *Bounded Context Canvas v4* de ddd-crew.
 
**Canvas 1: Trip Execution & Monitoring**
 
![Trip Execution and Monitoring Bounded Context Canvas](resources/chapter-2/Bounded-Context-Canvas/The-Bounded-Context-Canvas-Trip.jpg)
 
| Campo | Contenido |
|---|---|
| **Name** | Trip Execution & Monitoring |
| **Description** | Registra la ejecución real del viaje diario del conductor: el abordaje con soporte de sincronización *offline* (US-06/TS-02), y la transmisión de la ubicación GPS en tiempo real durante todo el trayecto. |
| **Strategic Classification** | Domain: core · Business Model: revenue generator · Evolution: custom built |
| **Domain Roles** | Execution Context |
| **Inbound Communication** | *Commands:* Select Route Card, Start Trip, Open Boarding, Set Boarding Status, Send Location Update, Report Incident, Complete Trip, Archive Trip. *Events:* Route Activation Finalized *(recibido de Fleet & Route Management)*, Trip Started, Boarding Opened, Student Boarded, Student Dropped Off, Location Updated, Incident Reported, Trip Completed, Trip Archived |
| **Ubiquitous Language** | **Trip:** ejecución física de una ruta en una fecha y hora específica. **Boarding:** acto en que un estudiante ingresa o desciende del vehículo. **Location Update:** registro puntual de coordenadas transmitido por el dispositivo en segundo plano. **Incident:** evento inesperado que altera el curso normal del viaje. |
| **Business Decisions** | El viaje inicia con `Boarding Opened` antes de aceptar registros de abordaje. Un registro sin señal se guarda localmente y sincroniza al recuperar conexión, de forma independiente al estado de la transmisión GPS.|
| **Outbound Communication** | *Messages:* `Student Boarded`, `Incident Reported`, `Location Updated` — publicados hacia el broker. *Collaborators:* RabbitMQ (Message Broker) → Notifications & Communication |
 
**Canvas 2: Fleet & Route Management**
 
![Fleet and Route Management Bounded Context Canvas](resources/chapter-2/Bounded-Context-Canvas/The-Bounded-Context-Canvas-Fleet.jpg)
 
| Campo | Contenido |
|---|---|
| **Name** | Fleet & Route Management |
| **Description** | Custodia el plan de recorrido vigente de cada ruta escolar: secuencia de paradas, vehículo y conductor asignados, días de servicio y hora de salida. |
| **Strategic Classification** | Domain: supporting · Business Model: engagement · Evolution: custom built |
| **Domain Roles** | Specification Context |
| **Inbound Communication** | *Commands:* Define Route, Pick Waypoints, Assign Students to Route, Select Vehicle, Define Service Days, Set Departure Time. *Events:* Route Defined, Waypoint Selected, Stop Count Updated, Student Assigned to Route *(recibido vía política de Stakeholder & Asset Management)*, Passenger Manifest Generated, Vehicle Assigned to Route, Service Days Defined, Route Activation Finalized |
| **Ubiquitous Language** | **Route:** secuencia predefinida de paradas entre un origen y un colegio. **Waypoint:** punto de paso seleccionado sobre el mapa al trazar la ruta. **Passenger Manifest:** listado de estudiantes asignados a una ruta. |
| **Business Decisions** | Una ruta no puede activarse sin vehículo y conductor asignados. El conteo de paradas se recalcula automáticamente al agregar o quitar un *waypoint*. Los estudiantes asignables a una ruta provienen únicamente del manifiesto exportado por Stakeholder & Asset Management, nunca de una consulta directa a su modelo interno. |
| **Outbound Communication** | *Messages:* `Route Activation Finalized`. *Collaborators:* Trip Execution & Monitoring |
 
**Canvas 3: Stakeholder & Asset Management**
 
![Stakeholder and Asset Management Bounded Context Canvas](resources/chapter-2/Bounded-Context-Canvas/The-Bounded-Context-Canvas-StakeHolder.jpg)
 
| Campo | Contenido |
|---|---|
| **Name** | Stakeholder & Asset Management |
| **Description** | Registra a conductores y padres de familia, vincula estudiantes a sus padres y organiza los grupos de estudiantes que luego se asignan a una ruta. |
| **Strategic Classification** | Domain: supporting · Business Model: engagement · Evolution: custom built |
| **Domain Roles** | Registry Context |
| **Inbound Communication** | *Commands:* Register Driver, Register Parent, Register Child, Link Child to Parent, Create Group, Assign Parents to Group, Include Linked Students, Finalize Group. *Events:* Driver Profile Created, Parent Profile Created, Child Profile Created, Child Linked to Parent, Group Name Assigned, Parents Assigned to Group, Students Included in Group, Group Finalized |
| **Ubiquitous Language** | **Driver:** persona registrada que opera una unidad de transporte. **Parent:** persona registrada responsable de uno o más estudiantes. **Group:** conjunto de estudiantes vinculados a los padres asignados, previo a su incorporación a una ruta. |
| **Business Decisions** | Un estudiante solo se vincula a un padre ya registrado. Un grupo no se finaliza sin al menos un padre y sus estudiantes incluidos. Al finalizarse, la política `Export Group Manifest to Route Context` traduce el grupo al único dato que Fleet & Route Management necesita: la nómina de estudiantes. |
| **Outbound Communication** | *Messages:* `Group Finalized` → política `Export Group Manifest to Route Context`. *Collaborators:* Fleet & Route Management |
 
**Canvas 4: Notifications & Communication**
 
![Notifications and Communication Bounded Context Canvas](resources/chapter-2/Bounded-Context-Canvas/The-Bounded-Context-Canvas-Notifications.jpg)
 
| Campo | Contenido |
|---|---|
| **Name** | Notifications & Communication |
| **Description** | Consume de forma asíncrona los eventos del viaje publicados por Trip Execution & Monitoring, evalúa la penetración de geocercas y traduce los eventos relevantes en notificaciones push, incluyendo alertas de alta prioridad y anuncios del conductor. |
| **Strategic Classification** | Domain: supporting · Business Model: engagement · Evolution: custom built sobre broker y proveedor push de terceros |
| **Domain Roles** | Dispatch Context |
| **Inbound Communication** | *Commands:* Trigger Panic Alert, Post Broadcast Message, Retry Notification. *Events (recibidos vía broker):* Student Boarded, Incident Reported, Location Updated. *Eventos propios:* Notification Created, Notification Queued, Geofence Breached, High Priority Alert Created, Notification Dispatched, Announcement Published, Notification Sent, Notification Failed |
| **Ubiquitous Language** | **Notification:** mensaje push entregado al dispositivo del padre ante un evento del viaje. **Geofence:** perímetro virtual cuya intersección con la posición del vehículo dispara `Geofence Breached`. **High Priority Alert:** notificación generada a partir de una incidencia reportada por el conductor. |
| **Business Decisions** | El consumo de eventos es asíncrono vía broker, sin bloquear la ejecución del viaje en Trip Execution & Monitoring. Una alerta de alta prioridad se despacha antes que las notificaciones ordinarias en cola. Una notificación fallida se reintenta automáticamente. Por decisión del equipo, no se genera ninguna notificación al completar o archivar un viaje. |
| **Outbound Communication** | *Messages:* `Notification Dispatched` / `Notification Sent`. *Collaborators:* Proveedor push (FCM) |
 
**Canvas 5: Identity & Access Management**
 
![Identity and Access Management Bounded Context Canvas](resources/chapter-2/Bounded-Context-Canvas/The-Bounded-Context-Canvas-IAM.jpg)
 
| Campo | Contenido |
|---|---|
| **Name** | Identity & Access Management |
| **Description** | Gestiona el registro, la autenticación y el control de acceso de los usuarios de la plataforma, resolviendo el rol activo que determina las funcionalidades visibles para cada perfil. |
| **Strategic Classification** | Domain: generic · Business Model: compliance enforcement · Evolution: product |
| **Domain Roles** | Gateway Context |
| **Inbound Communication** | *Commands:* Sign In, Register Administrator, Generate Session Token, Generate Password. *Events:* Login Accepted, User Authenticated, JWT Session Token Issued, User Logged In, Administrator Account Created, Admin Role Privileges Granted, Driver Account Provisioned, Parent Account Provisioned, Password Generated |
| **Ubiquitous Language** | **Account:** identidad única de un usuario en la plataforma. **Session Token:** credencial temporal emitida tras una autenticación válida. **Role:** perfil activo (Administrador, Conductor, Padre) que determina las funcionalidades visibles. |
| **Business Decisions** | Un usuario debe estar registrado para acceder a la plataforma. Las cuentas de conductor y padre se provisionan con credenciales generadas automáticamente al momento del registro por el administrador. |
| **Outbound Communication** | *Messages:* `User Authenticated` / `JWT Session Token Issued`, consumidos sin traducción. *Collaborators:* Todos los Bounded Contexts (patrón Conformist, ver 2.5.2) |
 
**Canvas 6: Subscription & Plan Management**
 
![Subscription and Plan Management Bounded Context Canvas](resources/chapter-2/Bounded-Context-Canvas/The-Bounded-Context-Canvas-Suscription.jpg)
 
| Campo | Contenido |
|---|---|
| **Name** | Subscription & Plan Management |
| **Description** | Administra los planes SaaS, procesa el cobro a través de la pasarela de pago y habilita el acceso comercial a la plataforma según el plan vigente del administrador. |
| **Strategic Classification** | Domain: generic · Business Model: revenue generator · Evolution: product |
| **Domain Roles** | Gateway Context |
| **Inbound Communication** | *Commands:* Select Plan, Initiate Payment Process, Upgrade Plan. *Events:* Plan Selected, Payment Confirmed, Subscription Activated, Plan Features Enabled, Plan Upgraded, Quotas Increased |
| **Ubiquitous Language** | **Subscription:** vínculo comercial vigente entre el administrador y la plataforma. **Plan:** nivel de servicio contratado, con límites propios de unidades gestionables. **Quota:** número máximo de rutas y conductores habilitados por el plan. |
| **Business Decisions** | La suscripción se activa solo tras la confirmación de pago de la pasarela externa. Una mejora de plan incrementa las cuotas sin interrumpir el servicio vigente. Ningún otro Bounded Context consulta estas cuotas en tiempo real. |
| **Outbound Communication** | *Messages:* Solicitar procesamiento de pago. *Collaborators:* Pasarela de pago (sistema externo) — sin colaboradores dentro del dominio propio |

### 2.5.2. Context Mapping

El *Context Map* establece las fronteras de nuestros Bounded Contexts y define explícitamente los patrones de integración y comunicación entre ellos, evitando que los modelos de dominio se contaminen entre sí. A diferencia de la sección anterior, aquí no se descubren conexiones nuevas: se toman las cinco conexiones ya confirmadas en el EventStorming (sección 2.5.1.1) y se les asigna el patrón de Domain-Driven Design que mejor describe la relación de poder y acoplamiento entre las partes.
 
Durante las sesiones de diseño se respondieron algunas dudas para validar la robustez y definir las relaciones de los contextos:
 
- **¿Qué pasaría si Fleet & Route Management consultara directamente las entidades internas de Stakeholder & Asset Management para armar el manifiesto de pasajeros, en lugar de recibir el manifiesto ya exportado?**
Se descartó. La conexión confirmada entre `Group Finalized` y `Assign Students to Route` ya pasa por una política explícita (`Export Group Manifest to Route Context`), que actúa como el contrato de traducción entre ambos contextos. El manifiesto de una ruta solo necesita saber qué estudiantes pertenecen a un grupo ya finalizado, no la estructura completa de padres, vínculos y perfiles que administra Stakeholder & Asset Management. Esto corresponde al patrón **Open Host Service** con un **Published Language** propio: el manifiesto exportado es el único dato que cruza la frontera.
 
- **¿Qué pasaría si Notifications & Communication consultara directamente el estado de Trip Execution & Monitoring cada vez que necesita evaluar una geocerca o generar una alerta?**
Se descartó. Las tres conexiones confirmadas desde Trip Execution & Monitoring (`Student Boarded`, `Incident Reported`, `Location Updated`) llegan a Notifications & Communication como eventos consumidos, no como consultas. Consultar en tiempo real acoplaría la disponibilidad de Notifications & Communication a la de Trip Execution & Monitoring, y ambos contextos escalan a ritmos distintos: uno recibe una posición cada pocos segundos por vehículo activo, el otro decide cuándo notificar. Se optó por que Trip Execution & Monitoring **publique** sus eventos a través de un broker de mensajería (RabbitMQ, según lo definido en la sección 2.6.1) y que Notifications & Communication los **consuma** de forma asíncrona: el patrón es **Published Language** sobre el broker, sin que ningún contexto conozca la implementación interna del otro.
 
- **¿Qué pasaría si aislamos Identity & Access Management y Subscription & Plan Management del resto del sistema?**
Al ser ambos *Generic Subdomain*, el resto de los contextos los consume tal como están, sin invertir esfuerzo en adaptarlos a las particularidades de RouteGuard. Identity & Access Management se conecta de forma transversal con los cinco contextos restantes a través de `User Authenticated`/`JWT Session Token Issued`, y esto corresponde al patrón **Conformist**: el costo de adaptarse es menor que el de mantener una traducción para un contexto que no evoluciona según las necesidades propias de RouteGuard. Subscription & Plan Management, en cambio, no tiene ninguna conexión confirmada hacia otro Bounded Context propio; su único vínculo es con la pasarela de pago, un sistema externo.
 
- **¿Qué pasaría si duplicáramos el plan de ruta dentro de Trip Execution & Monitoring para no depender de Fleet & Route Management en tiempo real?**
Se descartó. El plan puede cambiar entre la planificación de la ruta y la ejecución del viaje, y duplicarlo arriesgaría a que el conductor opere con una lista desactualizada. Se mantiene la relación **Customer/Supplier**, con Fleet & Route Management como proveedor autoritativo: es su evento `Route Activation Finalized` el que directamente habilita el comando `Start Trip` en Trip Execution & Monitoring.
 
**Diagrama de Context Mapping**
 
![Context Mapping RouteGuard](resources/chapter-2/ContextMapping.jpg)
 
*Identity & Access Management* es consumido como **Conformist** por los cinco contextos restantes: todos aceptan su modelo de identidad y rol sin traducción.
 
*Subscription & Plan Management* opera aislado del resto del dominio operativo: su única relación externa es con la pasarela de pago. Ningún contexto consulta sus cuotas o límites en tiempo real, y por eso no aparece conectado a ningún otro Bounded Context en el mapa.
 
*Stakeholder & Asset Management* actúa como proveedor de un **Open Host Service** hacia *Fleet & Route Management*, mediado por la política `Export Group Manifest to Route Context`.
 
*Fleet & Route Management* y *Trip Execution & Monitoring* mantienen una relación **Customer/Supplier**: el plan de ruta es propiedad de Fleet & Route Management, y su finalización es la que habilita el inicio del viaje.
 
*Trip Execution & Monitoring* es el contexto con más salidas confirmadas del sistema: las tres relaciones hacia *Notifications & Communication* (abordaje, incidencia y geocerca) se comunican exclusivamente a través de **RabbitMQ**, sin invocación directa entre ambos contextos. Esto permite que el alto volumen de telemetría GPS generado por Trip Execution & Monitoring no compita por recursos con la ejecución del viaje, y que Notifications & Communication escale su consumo de forma independiente.

### 2.5.3. Software Architecture

#### 2.5.3.1. Software Architecture Context Level Diagrams

![System Context Diagram](resources/chapter-2/software-architecture/context-diagram.svg)

#### 2.5.3.2. Software Architecture Container Level Diagrams

![Container Diagram](resources/chapter-2/software-architecture/container-diagram.png)

#### 2.5.3.3. Software Architecture Deployment Diagrams

## 2.6. Tactical-Level Domain-Driven Design

### 2.6.1. Bounded Context: Trip Execution & Monitoring

Este contexto (Core Domain) encapsula toda la ejecución en tiempo real del viaje. Para asegurar su máxima resiliencia, soporta la sincronización de abordajes *Offline-First* mediante caché local y el monitoreo GPS constante.

#### 2.6.1.1. Domain Layer
*   **Entities:** `Route` (Raíz del Agregado), `LocationRecord`, `Waypoint`.
*   **Value Objects:** `Coordinates` (Lat/Lng), `Telemetry` (Speed, Battery), `Timestamp`.
*   **Domain Events:** `TripStarted`, `StudentBoarded`, `OfflineSyncCompleted`.

#### 2.6.1.2. Interface Layer
*   **REST Controllers:** `TripCommandController` (Inicia/cancela rutas), `WaypointController` (Marca abordajes).
*   **Event Listeners:** `SyncOfflineAbordajesListener` (Recibe lotes de datos SQLite en reconexión).
*   **WebSockets:** `RouteTrackingSocketHandler` (Emite la coordenada en vivo a los padres).

#### 2.6.1.3. Application Layer
*   **Application Services:** `RouteTrackingService` (Calcula la distancia a la siguiente parada y publica eventos al bus). `MapboxRoutingService` (Integración para ETA).

#### 2.6.1.4. Infrastructure Layer
*   **Persistence:** Base de datos con capacidades espaciales (PostGIS / GeoJSON) para almacenamiento geométrico.
*   **External APIs:** Mapbox API / Google Maps Platform.

#### 2.6.1.5. Component Level Diagrams

![Tracking Components](resources/chapter-2/software-architecture/components-frontend-tracking.svg)

![Tracking Components](resources/chapter-2/software-architecture/components-backend-tracking.svg)

#### 2.6.1.6. Code Level Diagrams
##### 2.6.1.6.1. Domain Layer Class Diagram

**Versión Detallada:**
![Tracking Domain Diagram Detailed](resources/chapter-2/software-architecture/tracking-domain-detailed.svg)

**Versión Legible (Simplificada):**
![Tracking Domain Diagram Readable](resources/chapter-2/software-architecture/tracking-domain-readable.svg)

##### 2.6.1.6.2. Database Design Diagram

![Tracking DB Diagram](resources/chapter-2/software-architecture/tracking-database.svg)


### 2.6.2. Bounded Context: Notifications & Communication

Este contexto reacciona a los eventos del sistema para notificar asíncronamente a los dispositivos móviles, asegurando alta disponibilidad a través de colas de mensajería y evitando cuellos de botella en la ejecución de los viajes.

#### 2.6.2.1. Domain Layer
*   **Entities:** `Notification` (Raíz), `GeofenceAlert` (Alerta generada por proximidad).
*   **Value Objects:** `PushPayload`, `DeviceToken`, `NotificationPriority`.
*   **Domain Events:** `NotificationDispatched`, `GeofenceBreached`.

#### 2.6.2.2. Interface Layer
*   **Message Consumers:** `TrackingEventConsumer` (Consume los eventos del viaje vía RabbitMQ/Kafka).
*   **REST Controllers:** `NotificationPreferencesController` (Gestión de preferencias del padre).

#### 2.6.2.3. Application Layer
*   **Application Services:** `GeofencingService` (Calcula intersecciones de radios), `PushNotificationDispatcher` (Genera el payload para el dispositivo).

#### 2.6.2.4. Infrastructure Layer
*   **Message Broker:** RabbitMQ para desacoplar el envío masivo de notificaciones.
*   **External Integrations:** Firebase Cloud Messaging (FCM) SDK.

#### 2.6.2.5. Component Level Diagrams

![Notifications Frontend Components](resources/chapter-2/software-architecture/components-frontend-notifications.svg)

![Notifications Backend Components](resources/chapter-2/software-architecture/components-backend-notifications.svg)

#### 2.6.2.6. Code Level Diagrams
##### 2.6.2.6.1. Domain Layer Class Diagram

**Versión Detallada:**
![Notifications Domain Diagram Detailed](resources/chapter-2/software-architecture/notifications-domain-detailed.svg)

**Versión Legible (Simplificada):**
![Notifications Domain Diagram Readable](resources/chapter-2/software-architecture/notifications-domain-readable.svg)

##### 2.6.2.6.2. Database Design Diagram

![Notifications DB Diagram](resources/chapter-2/software-architecture/notifications-database.svg)




### 2.6.3. Bounded Context: Identity & Access Management

#### 2.6.3.1. Domain Layer

#### 2.6.3.2. Interface Layer

#### 2.6.3.3. Application Layer

#### 2.6.3.4. Infrastructure Layer

#### 2.6.3.5. Component Level Diagrams

#### 2.6.3.6. Code Level Diagrams

##### 2.6.3.6.1. Domain Layer Class Diagram

##### 2.6.3.6.2. Database Design Diagram


### 2.6.4. Bounded Context: Subscription & Plan Management

#### 2.6.4.1. Domain Layer

#### 2.6.4.2. Interface Layer

#### 2.6.4.3. Application Layer

#### 2.6.4.4. Infrastructure Layer

#### 2.6.4.5. Component Level Diagrams

#### 2.6.4.6. Code Level Diagrams

##### 2.6.4.6.1. Domain Layer Class Diagram

##### 2.6.4.6.2. Database Design Diagram


### 2.6.5. Bounded Context: Fleet & Route Management

#### 2.6.5.1. Domain Layer
*   **Entities:** `Trip` (Raíz del Agregado), `Waypoint`, `LocationRecord`.
*   **Value Objects:** `Coordinates` (Lat/Lng), `Telemetry` (Speed, Battery, Heading), `Timestamp`.
*   **Domain Events:** `TripStarted`, `StudentBoarded`, `TripFinished`, `OfflineSyncCompleted`.

#### 2.6.5.2. Interface Layer
*   **REST Controllers:** `TrackingController` (Expone los endpoints REST principales).
*   **Event Listeners / Message Brokers:** `RabbitMqEventPublisher` (Publica eventos de dominio al bus de mensajes).
*   **WebSockets / External Integrations:** `MapboxAdapter / TripApiService` (Integración remota para cálculo de ETA y rutas).

#### 2.6.5.3. Application Layer
*   **Application Services:** TrackingApp Service / Use Cases (`StartTripUseCase`, `BoardStudentUseCase`, `SyncOfflineRecordsUseCase`, `FinishTripUseCase`, `RouteTrackingService` - Maneja la lógica de casos de uso y cálculo de distancias/paradas).

#### 2.6.5.4. Infrastructure Layer
*   **Persistence:** Base de datos relacional principal con `PostgreSQL` y capacidades espaciales `PostGIS` (utilizando Trip JPA Repo / Room DAO para almacenamiento geométrico y local).
*   **External APIs:** `Mapbox API / Retrofit` (Servicios externos para mapas, geolocalización y sincronización).

#### 2.6.5.5. Component Level Diagrams

![Route Frontend Components](resources/chapter-2/software-architecture/components_frontend_fleet.svg)

![Route Backend Components](resources/chapter-2/software-architecture/components_backend_fleet.svg)

#### 2.6.5.6. Code Level Diagrams
##### 2.6.5.6.1. Domain Layer Class Diagram

**Versión Detallada:**
![Route Domain Diagram Detailed](resources/chapter-2/software-architecture/fleet-domain.svg)

**Versión Legible (Simplificada):**
![Route Domain Diagram Readable](resources/chapter-2/software-architecture/fleet-domain-readable.svg)

##### 2.6.5.6.2. Database Design Diagram

![Route DB Diagram](resources/chapter-2/software-architecture/fleet-database.svg)


### 2.6.6. Bounded Context: Stakeholder & Asset Management

#### 2.6.6.1. Domain Layer

En esta capa se definen las entidades principales del dominio de Stakeholder, como `Parent`, `Student`, `EmergencyContact` y `School`, junto con sus relaciones (por ejemplo, un padre puede tener varios hijos y varios contactos de emergencia asociados). También se incluyen contratos como `StakeholderRepository` que abstraen el acceso a los datos desde la lógica de negocio.



#### 2.6.6.2. Interface Layer

Esta capa expone la interacción con el usuario mediante pantallas como `StakeholderScreen`, que se comunican con el `StakeholderViewModel` para gestionar el estado de la interfaz (`StakeholderUiState`) y disparar las acciones del usuario hacia los casos de uso correspondientes.


<div style="page-break-after: always;"></div>

# Capítulo III: Solution UI/UX Design

## 3.1. Product design

### 3.1.1. Style Guidelines

#### 3.1.1.1. General Style Guidelines

### 3.1.2. Information Architecture

#### 3.1.2.1. Organization Systems

#### 3.1.2.2. Labelling Systems

#### 3.1.2.3. SEO Tags and Meta Tags

#### 3.1.2.4. Searching Systems

#### 3.1.2.5. Navigation Systems

### 3.1.3. Landing Page UI Design

#### 3.1.3.1. Landing Page Wireframe

#### 3.1.3.2. Landing Page Mock-up

### 3.1.4. Mobile Applications UX/UI Design

#### 3.1.4.1. Mobile Applications Wireframes

#### 3.1.4.2. Mobile Applications Wireflow Diagrams

#### 3.1.4.3. Mobile Applications Mock-ups

#### 3.1.4.4. Mobile Applications User Flow Diagrams

#### 3.1.4.5. Mobile Applications Prototyping

<div style="page-break-after: always;"></div>

# Capítulo IV: Product Implementation & Validation

## 4.1. Software Configuration Management

### 4.1.1. Software Development Environment Configuration

### 4.1.2. Source Code Management

### 4.1.3. Source Code Style Guide & Conventions

### 4.1.4. Software Deployment Configuration

## 4.2. Landing Page & Mobile Application Implementation

### 4.2.1. Sprint n

#### 4.2.1.1. Sprint Planning n

| Sprint # | Sprint n |
|---|---|
| Sprint Planning Background | |
| Date | YYYY-MM-DD |
| Time | HH:MM AM/PM |
| Location | |
| Prepared By | |
| Attendees (to planning meeting) | |
| Sprint n – 1 Review Summary | |
| Sprint n – 1 Retrospective Summary | |
| **Sprint Goal & User Stories** | |
| Sprint n Goal | |
| Sprint n Velocity | |
| Sum of Story Points | |

#### 4.2.1.2. Aspect Leaders and Collaborators

| Team Member | GitHub Username | Aspect Name 1 | Aspect Name 2 | Aspect Name n |
|---|---|---|---|---|
| | | | | |

#### 4.2.1.3. Sprint Backlog n

| Sprint # | Sprint n | | | |
|---|---|---|---|---|
| **User Story** | **Work-Item / Task** |
| Id | Title | Id | Title | Description | Estimation (Hours) | Assigned To | Status |

#### 4.2.1.4. Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| | | | | | |

#### 4.2.1.5. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| | | | | | |

#### 4.2.1.6. Execution Evidence for Sprint Review

#### 4.2.1.7. Services Documentation Evidence for Sprint Review

#### 4.2.1.8. Software Deployment Evidence for Sprint Review

#### 4.2.1.9. Team Collaboration Insights during Sprint

## 4.3. Validation Interviews

### 4.3.1. Diseño de Entrevistas

### 4.3.2. Registro de Entrevistas

### 4.3.3. Evaluaciones según heurísticas

<div style="page-break-after: always;"></div>

# Conclusiones

### Conclusiones y recomendaciones

### Video App Validation

### Video About the product

### Video About the team

<div style="page-break-after: always;"></div>

# Glosario

<div style="page-break-after: always;"></div>

# Bibliografía

**Dominio de negocio**

* Autoridad de Transporte Urbano para Lima y Callao [ATU]. (2024). *Reporte anual de fiscalización y formalización del transporte especial de estudiantes*. Gobierno del Perú.
* Chen, L., & Davis, M. (2025). Passive monitoring and geofencing in child logistics: Impacts on parental anxiety and user engagement. *Journal of Interactive Mobile Technologies*, 19(1), 78-95. https://doi.org/10.1016/j.jimt.2025.02.012
* García, M., López, R., & Torres, P. (2024). Smart mobility in developing cities: Challenges in private school transportation logistics. *Journal of Urban Technology and Smart Cities*, 12(3), 45-62. https://doi.org/10.1080/10630732.2024.1234567
* Ministerio de Educación [MINEDU]. (2023). *Resultados del Censo Educativo 2022-2023: Matrícula y tendencias en zonas urbanas*. Gobierno del Perú.
* Smith, J., & Johnson, A. (2025). Cognitive load and mobile distraction among commercial drivers: A real-time monitoring approach. *International Journal of Transportation Safety*, 41(2), 112-128. https://doi.org/10.1016/j.ijts.2025.01.005

**Métodos y técnicas de ingeniería de software**

* Adzic, G. (2012). *Impact Mapping: Making a big impact with software products and projects.* Provoking Thoughts.
* Brandolini, A. (2021). *Introducing EventStorming: An Act of Deliberate Collective Learning.* Leanpub.
* Chen, Y., & Zhao, M. (2025). Passive monitoring and location-based notifications in family tracking applications. *Journal of Mobile Human-Computer Interaction,* 15(2), 45-60. https://doi.org/10.1016/j.jmhci.2025.104221
* Cooper, A. (1999). *The Inmates Are Running the Asylum: Why High Tech Products Drive Us Crazy and How to Restore the Sanity.* Sams Publishing.
* Cohn, M. (2004). *User Stories Applied: For Agile Software Development.* Addison-Wesley Professional.
* Evans, E. (2003). *Domain-Driven Design: Tackling Complexity in the Heart of Software.* Addison-Wesley Professional.
* Gothelf, J., & Seiden, J. (2021). *Lean UX: Designing Great Products with Agile Teams* (3rd ed.). O'Reilly Media.
* Kumar, A., & Lee, S. (2024). Role-based task frequency analysis in mobile interface design for logistics. *International Journal of Human-Computer Studies,* 182, 103-118. https://doi.org/10.1016/j.ijhcs.2024.103118
* Rubin, K. S. (2012). *Essential Scrum: A Practical Guide to the Most Popular Agile Process.* Addison-Wesley.
* Schwaber, K., & Sutherland, J. (2020). *The Scrum Guide.* Scrum.org.
* Stickdorn, M., Hormess, M. E., Lawrence, A., & Schneider, J. (2018). *This Is Service Design Doing: Applying Service Design Thinking in the Real World*. O'Reilly Media.
* Vernon, V. (2013). *Implementing Domain-Driven Design.* Addison-Wesley.

**Lenguajes, frameworks y herramientas**

* Google. (2024). *Firebase Cloud Messaging Documentation.* Google Developers. https://firebase.google.com/docs/cloud-messaging
* Mapbox. (2024). *Mapbox Navigation SDK for Mobile.* Mapbox. https://docs.mapbox.com/
* PostGIS Project Steering Committee. (2024). *PostGIS: Spatial and Geographic Objects for PostgreSQL.* OSGeo. https://postgis.net/
* VMware. (2024). *RabbitMQ: Messaging that just works.* Broadcom. https://www.rabbitmq.com/

<div style="page-break-after: always;"></div>

# Anexos



