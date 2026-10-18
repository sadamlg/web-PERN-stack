# web-PERN-stack

Plantilla reutilizable para iniciar proyectos web con un stack PERN, complementado con Next.js y Tailwind CSS. Su propósito es ofrecer una base de desarrollo coherente y reproducible, independiente del dominio o las funcionalidades de cada aplicación.

## Stack

| Área | Tecnología | Propósito |
|---|---|---|
| Frontend | Next.js, React y Tailwind CSS | Interfaz web y renderizado con React |
| Backend | Node.js y Express | API REST y lógica de servidor |
| Base de datos | PostgreSQL | Persistencia relacional |
| ORM y migraciones | Prisma ORM y Prisma Migrate | Acceso tipado a PostgreSQL y gestión versionada del esquema |
| Procesamiento asíncrono | BullMQ, Redis y worker Node.js | Encolar y procesar trabajos fuera de la petición HTTP |
| Correo de desarrollo | Mailpit | Captura y consulta local de correos generados durante el desarrollo |
| Entorno local | Docker Engine y Docker Compose | Construcción y ejecución coordinada de los servicios de desarrollo |

## Propósito

La plantilla reúne estos componentes para levantar y conectar los servicios locales mediante una guía ordenada, sin depender de instalaciones de Node.js en el equipo anfitrión.

La secuencia de construcción, la red de servicios y las comprobaciones están en la [guía del entorno local con Docker Compose](docs/docker/guia-de-construccion-docker-compose.md).

Esta plantilla no corresponde a una aplicación de negocio específica. Cada proyecto derivado definirá sus propias funcionalidades, variables de entorno y uso de los servicios auxiliares.

## Ramas

- `develop` es la rama predeterminada y punto de integración del trabajo.
- `main` conserva la versión estable de la plantilla.
- Los cambios se trabajan en ramas dedicadas y se integran mediante pull requests.
- GitHub elimina automáticamente las ramas de origen después de fusionar sus pull requests.
