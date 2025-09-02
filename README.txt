1. Hosting:
   - Subir ZIP y extraerlo....
   - index.html en raíz o public_html.
   - pdfs/ con el PDF dentro.
   - Reemplaza TU_LINK_DE_PAGO en index.html con tu link de Mercado Pago real.
   
2. Google Sheets + Apps Script:
   - Crear hoja con columnas: Email | FechaPago | Descargado
   - Crear hoja "Tokens" para almacenar tokens de descarga.
   - Crear Apps Script con doPost y doGet (descarga segura via token).
   - Publicar como Web App (acceso: cualquiera, incluso anónimo).
   - Reemplazar TU_WEB_APP_URL en success.html y en index.html si fuera necesario.

3. Correo:
   - Apps Script usa MailApp.sendEmail desde tu cuenta de Google.
   - Asegúrate de tener permisos de envío activados.
   - La descarga se envía automáticamente al correo confirmado.


