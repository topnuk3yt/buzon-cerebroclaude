---
layout: default
title: CerebroClaude Buzón
---

# CerebroClaude Buzón

Actualizado el 26 de octubre de 2026.

CerebroClaude Buzón es una conexión personal de rclone que traslada encargos de Google Drive a las máquinas del titular. No ofrece registro ni acceso a otras personas.

## Privacidad

La conexión usa la API de Google Drive con autorización del titular. El permiso de Google permite acceder a los archivos de Drive; la configuración de rclone limita las operaciones del buzón a la carpeta elegida. Esa configuración no reduce el alcance del permiso concedido por Google.

Los encargos admitidos se copian al repositorio privado de trabajo del titular en GitHub. Los asistentes autorizados por el titular pueden leerlos para resolverlos y generar los resultados. Solo después de comprobar la publicación en ese repositorio se envía el original a la papelera de Drive. Los resultados y el estado de las máquinas también se guardan en el buzón. El traslado lo ejecutan las máquinas del titular; esta página no recibe archivos ni credenciales.

Las credenciales se conservan en las máquinas del titular, fuera del repositorio de trabajo y con permisos de acceso restringidos. Los archivos que ya se hayan copiado quedan sujetos al historial de ese repositorio. Revocar la autorización de Google detiene el acceso futuro y no elimina esas copias anteriores.

El titular puede revisar y revocar el acceso desde los ajustes de seguridad de su Cuenta de Google. Para consultar esta conexión puede contactar por la dirección de asistencia que aparece en la pantalla de consentimiento de Google.

Esta página describe la conexión de uso personal del titular. Si se habilita para otras personas o cambia el tratamiento de los archivos, su descripción debe actualizarse antes de ese cambio.
