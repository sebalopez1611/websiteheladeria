# Fuente de Vida - Sitio Web de Heladería

&#x20;&#x20;

## 📖 Descripción del Proyecto

**Fuente de Vida** es un sitio web diseñado para una heladería, enfocado en pedidos mayoristas gestionados vía WhatsApp. Este proyecto busca ofrecer una experiencia de usuario intuitiva, ágil y optimizada para dispositivos móviles y de escritorio.

### 🧐 Motivación

* Centralizar la visualización de productos en categorías claras (cubetas, palitos frutales, palitos cremosos, conos y Chupa Chups).
* Automatizar el proceso de pedido para reducir errores y agilizar tiempos de respuesta.
* Aprovechar la popularidad de WhatsApp como canal de comunicación para pedidos mayoristas.

### 🛠️ Características

* Navegación por categorías de productos.
* Proceso de pedido guiado en 4 pasos.
* Integración directa con WhatsApp para envío de pedidos.
* Diseño responsive y optimizado para SEO.

## 🎬 Demo en Vivo

* Sitio desplegado en Vercel: [https://fuentedevida.vercel.app/](https://fuentedevida.vercel.app/)
* Captura de pantalla:
* ![image](https://github.com/user-attachments/assets/7fd59377-a048-4292-9372-24ca197cdc0d)
* ![image](https://github.com/user-attachments/assets/c02a4e8a-9813-4eee-acb9-2a10ecdca709)
* ![image](https://github.com/user-attachments/assets/a247ae45-fc83-4a2b-8704-3ae861485a72)
* ![image](https://github.com/user-attachments/assets/a05183e7-11c3-44a1-9171-561f02e8d338)
* ![image](https://github.com/user-attachments/assets/88f6111d-bcf5-4777-9492-7ccd1fa364cc)
* ![image](https://github.com/user-attachments/assets/37f1e8f8-92db-4d68-a45e-b94d9d2078ea)



## 📋 Tabla de Contenidos

* [Tech Stack](#tech-stack)
* [Arquitectura](#arquitectura)
* [Estructura de Carpetas](#estructura-de-carpetas)
* [Instalación](#instalaci%C3%B3n)
* [Uso](#uso)
* [Contribuir](#contribuir)
* [Licencia](#licencia)
* [Contacto](#contacto)

## 🏗️ Tech Stack

| Tecnología   | Propósito                           |
| ------------ | ----------------------------------- |
| Next.js      | Framework React para SSR/SSG        |
| TypeScript   | Tipado estático para mayor robustez |
| Tailwind CSS | Estilos utilitarios y responsive    |
| pnpm         | Gestión eficiente de dependencias   |
| Vercel       | Despliegue automático en la nube    |

## 🏛️ Arquitectura

El siguiente diagrama muestra el flujo de interacción del usuario y los componentes principales:

```mermaid
flowchart LR
  A[Usuario] --> B[Navegador (Next.js)]
  B --> C[Catálogo de Productos]
  C --> D[Proceso de Pedido (4 Pasos)]
  D --> E[API de WhatsApp (wa.me link)]
  E --> F[Heladería Fuente de Vida]
```

## 📁 Estructura de Carpetas

```
websiteheladeria/
├─ components/      # Componentes React reutilizables
├─ pages/           # Páginas y rutas Next.js
├─ public/          # Recursos estáticos (imágenes, íconos)
├─ styles/          # CSS global y configuraciones de Tailwind
├─ docs/            # Documentación interna y capturas
├─ next.config.mjs  # Configuración de Next.js
├─ tailwind.config.ts
├─ postcss.config.mjs
├─ tsconfig.json
├─ package.json
└─ pnpm-lock.yaml
```

## ⚙️ Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/sebalopez1611/websiteheladeria.git
   ```
2. Navega a la carpeta del proyecto:

   ```bash
   cd websiteheladeria
   ```
3. Instala las dependencias con pnpm:

   ```bash
   pnpm install
   ```
4. Inicia el servidor de desarrollo:

   ```bash
   pnpm dev
   ```
5. Abre en tu navegador [http://localhost:3000](http://localhost:3000).

## 🎯 Uso

1. Selecciona la categoría de producto.
2. Completa el formulario guiado de 4 pasos (cantidad, datos de cliente, etc.).
3. Haz clic en **Enviar por WhatsApp** para abrir la aplicación con el pedido preconfigurado.
4. Envía el mensaje y recibe confirmación directamente con la heladería.

## 🤝 Contribuir

Las contribuciones son bienvenidas:

1. Haz un **fork** del proyecto.
2. Crea una **branch** (`git checkout -b feature/nombre-de-la-feature`).
3. Realiza tus **commits** con mensajes descriptivos.
4. Haz **push** a tu rama y abre un **Pull Request**.

## 📜 Licencia

Este proyecto está bajo la licencia **MIT**. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## ✉️ Contacto

Desarrollado por **Sebas López**:

* Correo: [sebalopez1611@gmail.com](mailto:sebalopez1611@gmail.com)
* Página web: [Fuente de Vida](https://fuentedevida.vercel.app/)
