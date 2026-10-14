NEXORA AI — paquete de publicación Vercel

1. Descomprimí este ZIP.
2. Subí index.html a la raíz del repositorio GitHub conectado a Vercel (no dentro de una subcarpeta).
3. En Vercel > Settings > Build and Deployment:
   - Framework Preset: Other
   - Build Command: vacío / Override desactivado
   - Output Directory: vacío / Override desactivado
   - Root Directory: ./ (raíz del repositorio)
4. Guardá y hacé un nuevo deployment desde Deployments > Redeploy, o subí el cambio a GitHub.
5. Abrí la URL HTTPS del proyecto en Chrome Android y aceptá el permiso de cámara.

Requisitos: conexión a internet para descargar Three.js y MediaPipe desde CDN. Usá archivos .glb autocontenidos para modelos 3D. La calidad del tracking depende del dispositivo, iluminación y navegador. Es un prototipo técnico, no una aplicación comercial terminada.
