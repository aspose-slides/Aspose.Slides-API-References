---
title: PresentationInfo
second_title: Aspose.Sildes para referencia de API de .NET
description: Información sobre el archivo de presentación
type: docs
weight: 9350
url: /es/aspose.slides/presentationinfo/
---

## Clase PresentationInfo

Información sobre el archivo de presentación

```csharp
public sealed class PresentationInfo : IPresentationInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsEncrypted](../../aspose.slides/presentationinfo/isencrypted) { get; } | Obtiene True si la presentación enlazada está encriptada, de lo contrario False. Booleano de solo lectura. |
| [IsPasswordProtected](../../aspose.slides/presentationinfo/ispasswordprotected) { get; } | Obtiene un valor que indica si una presentación enlazada está protegida por una contraseña para abrir. |
| [IsWriteProtected](../../aspose.slides/presentationinfo/iswriteprotected) { get; } | Obtiene un valor que indica si una presentación enlazada está protegida contra escritura. |
| [LoadFormat](../../aspose.slides/presentationinfo/loadformat) { get; } | Obtiene el formato de la presentación enlazada. Solo lectura [`LoadFormat`](../loadformat). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CheckPassword](../../aspose.slides/presentationinfo/checkpassword)(string) | Verifica si una contraseña es correcta para una presentación protegida con contraseña de apertura. |
| [CheckWriteProtection](../../aspose.slides/presentationinfo/checkwriteprotection)(string) | Verifica si una contraseña para modificar es correcta para una presentación protegida contra escritura. |
| [ReadDocumentProperties](../../aspose.slides/presentationinfo/readdocumentproperties)() | Obtiene las propiedades del documento de la presentación enlazada. |
| [UpdateDocumentProperties](../../aspose.slides/presentationinfo/updatedocumentproperties)(IDocumentProperties) | Actualiza las propiedades de la presentación enlazada. |
| [WriteBindedPresentation](../../aspose.slides/presentationinfo/writebindedpresentation#writebindedpresentation)(Stream) | Escribe la presentación enlazada en un flujo. |
| [WriteBindedPresentation](../../aspose.slides/presentationinfo/writebindedpresentation#writebindedpresentation_1)(string) | Escribe la presentación enlazada en un archivo. |

### Ver También

* interfaz [IPresentationInfo](../ipresentationinfo)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->