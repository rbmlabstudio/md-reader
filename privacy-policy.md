# Política de privacidad de MD Reader

Última actualización: 8 de noviembre de 2026. Primera distribución prevista: Android.

MD Reader procesa documentos Markdown en tu dispositivo. No tiene cuentas, servidores propios, anuncios ni analítica. El código propio no envía documentos, imágenes, búsquedas ni datos de uso a un servidor. La aplicación Android no solicita INTERNET; un permiso ACCESS_NETWORK_STATE aportado por dependencias permite consultar conectividad, no transmitir archivos.

## Almacenamiento local y borrado

La app guarda copias privadas de los Markdown importados, imágenes locales vinculadas, ediciones, marcadores, favoritos, progreso y preferencias. Editar modifica la copia privada y conserva temporalmente un respaldo recuperable; no modifica el archivo externo. Borrar desde Biblioteca elimina el documento privado y sus recursos y datos asociados. Desinstalar o borrar los datos de Android elimina toda la biblioteca local. Estos datos se excluyen del respaldo automático de Android. Conserva tus archivos originales para recuperarlos si desinstalas.

## Archivos y carpetas autorizados

Puedes importar archivos independientes o autorizar carpetas mediante el selector de Android. El acceso se limita a los archivos y carpetas que autorizas. La app conserva localmente los permisos persistentes, la URI del Markdown original y las carpetas, la identidad del original y la asociación entre sus rutas relativas e imágenes para resolverlas automáticamente, incluso después de editar la copia privada. Puedes autorizar solo la carpeta de imágenes; no necesita contener el Markdown. Un permiso de carpeta cubre sus subcarpetas, nunca rutas fuera del árbol autorizado. No se solicita acceso a todos los archivos del dispositivo.

En Pro se comprueba primero el acceso existente y se copia solo la imagen solicitada tras validar formato y límites. Si falta acceso, Android pide autorizar la carpeta una vez; al volver se carga automáticamente. Las importaciones anteriores pueden identificar su origen por nombre, tamaño y hash entre los permisos y proyectos ya autorizados. Puedes cancelar la búsqueda y revocar los permisos de carpetas desde Ajustes; las copias ya importadas permanecen disponibles. La búsqueda y lectura tienen límites; los proveedores en nube pueden requerir conexión gestionada por Android o el proveedor.

## Compra opcional Pro

Google Play procesa el pago y su SDK entrega al proceso de la app los datos necesarios para consultar y finalizar la compra. El código propio no guarda tokens ni recibos ni recibe números de tarjeta. Guarda solo un resumen local (producto, identificador de transacción y fechas) para acceso sin conexión. Una consulta fallida conserva el acceso confirmado previamente; una consulta exitosa que ya no reconozca la compra lo retira. No hay concesión Pro automática por tener documentos. Las condiciones y el tratamiento de Google Play corresponden a Google.

## Texto a voz, notificaciones y enlaces

El texto se entrega al motor TTS que eliges en Android. Algunas voces pueden usar servidores de su proveedor; instala una voz offline si necesitas evitar ese procesamiento. La ausencia de INTERNET en MD Reader no impide que otro proceso, incluido el motor de voz o Play, utilice su propia conexión. La aplicación muestra el requisito de red cuando el sistema lo informa.

Las notificaciones son opcionales y muestran controles genéricos, sin texto del documento. El servicio en primer plano mediaPlayback permite lectura Pro con pantalla bloqueada. Los enlaces web o de correo se abren en otra aplicación solo tras tu acción y confirmación; entonces se aplica la política de esa aplicación. Los enlaces locales Markdown se resuelven en la biblioteca. No se descargan imágenes remotas.

## Contacto y cambios

Responsable: **RBMLAB Studio**. Contacto: **rbmlabstudio@gmail.com**. Esta política está disponible en Ajustes, sin conexión, y en su versión pública: https://rbmlabstudio.github.io/md-reader/privacy-policy.html. Las actualizaciones se publicarán en esa misma dirección e indicarán la fecha de revisión.

MD Reader no está diseñada específicamente para menores de edad.

---

# MD Reader privacy policy

Updated November 8, 2026. Initial distribution: Android.

MD Reader processes Markdown on your device. It has no accounts, own servers, ads or analytics. Its own code does not upload documents, images, searches or usage data. The Android app does not request INTERNET. ACCESS_NETWORK_STATE from dependencies can inspect connectivity; it does not grant network access.

Imported Markdown, linked raster images, edits, bookmarks, favorites, progress and preferences stay in private storage, excluded from Android automatic backups. Edits affect only the private copy and retain a temporary recovery backup. Library deletion removes the private document and associated resources. Uninstalling or clearing app data removes the library; keep original files separately.

Android's document selector grants access only to authorized files and folders. Permissions, original Markdown URI, folder URIs, fingerprints and relative image-folder associations are retained locally, including after private edits. You can authorize an image-only folder without including its Markdown. A folder grant covers its subfolders; no all-files access is requested. Pro checks existing access first and copies only the requested validated image. If access is missing, authorize its folder once and the image loads automatically when you return. Older imports may identify their origin by name, size and hash among existing grants/projects. Cancel lookups or revoke folder access in Settings; imported private copies remain. Search/read limits apply. Cloud providers may use their own network connections.

Google Play handles optional Pro payments. Its SDK delivers purchase information to the app process for checking and acknowledging purchases. Own code does not persist tokens or receipts or receive card numbers. Only product, transaction identifier and dates are cached locally. A failed query preserves confirmed offline access; a successful query without the purchase removes access. Importing documents never grants Pro. Google's policies govern its payment service.

Document text is passed to your chosen Android TTS engine. Some voices may process text on their provider's servers; install an offline voice if needed. Other processes, including TTS and Play, can use their own network permission even though MD Reader has none. Network requirements are displayed when reported by the system. Optional notifications contain generic playback controls, without document text. The mediaPlayback foreground service supports Pro background reading. Web and email links open in other apps only after your action and confirmation. Remote images are not downloaded.

Controller: **RBMLAB Studio**. Support: **rbmlabstudio@gmail.com**. This policy is available offline in Settings and online at https://rbmlabstudio.github.io/md-reader/privacy-policy.html. Updates will be published at that address with their revision date.

MD Reader is not specifically designed for children.
