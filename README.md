# 💌 Campañas por Correo de Kiosko (Semana Santa)

Este repositorio contiene las plantillas desarrolladas para la campaña de **Envío Gratis post-Semana Santa**. 

Se ha priorizado un diseño premium, estético y muy optimizado para el uso moderno del email marketing (responsive, mobile-first, y seguro con diferentes tipos de administradores y clientes de correo).

## 🎨 Especificaciones del Estilo & Código
- **Color Principal de Marca:** `#EB6F79` (Aplicado para destacar el copy y la separación de atención en cada uno de los envíos).
- **Enfoque Visual:** Estética centrada, aireada (buen uso del *padding* y *whitespace*) con tipografía que facilita la lectura en el móvil.
- **Tipografía Base:** Utiliza fuentes seguras de sistema (`Helvetica Neue, Helvetica, Arial, sans-serif`) para evitar fallos de renderizado en plataformas como Outlook o Gmail Web.
- **Estructura Interna:** Código "A prueba de fallos". Todas las maquetaciones fueron construidas utilizando un sistema jerárquico `<table align="center">` (Ghost tables). Esto garantiza la alineación perfecta en clientes *mso* (Microsoft Outlook Desktop) y es una de las reglas de oro para lograr consistencia en los diseños de correo.

## 🗂 Estructura de Navegación 
- `index.html`: Portal general donde podrás acceder fácilmente a cualquier template. Posee un estilo moderno con `Vanilla CSS` de alto impacto.
- `email-1.html`: Plantilla #1 "Tenemos algo para ti" — Destaca un botón *bulletproof* de WhatsApp (color verde estándar y estructurado sin importar la vista previa del cliente de correo). Incluye inserción de un GIF.
- `email-2.html`: Plantilla #2 "Seguimiento" — Usa un enfoque curado mostrando productos hermosamente ordenados de manera continua.
- `email-3.html`: Plantilla #3 "Últimas Horas de Promoción" — Cierre firme para evocar urgencia pura.

## 🚀 Cómo Integrar las Plantillas
1. Abre tu plataforma de Email Marketing deseada (Klaviyo, Mailchimp, Brevo, etc).
2. Selecciona crear nueva campaña mediante **"Custom HTML"** o **Cargar Código**.
3. Copia de forma íntegra el código fuente del respectivo `email-*.html` y pégalo allí.
4. Asegúrate posteriormente de subir las imágenes (referenciadas en `assets/...` actualmente) a la librería de la plataforma, y sustituye la URL de las mismas dentro de las etiquetas `src` de las imágenes en el código HTML con la URL web final.
