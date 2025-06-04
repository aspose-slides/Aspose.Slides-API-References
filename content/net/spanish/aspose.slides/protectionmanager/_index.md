---
title: ProtectionManager
second_title: Aspose.Slides para .NET Referencia de API
description: Gestión de protección por contraseña de presentaciones.
type: docs
weight: 9410
url: /es/aspose.slides/protectionmanager/
---

## Clase ProtectionManager

Gestión de protección por contraseña de presentaciones.

```csharp
public sealed class ProtectionManager : IProtectionManager
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EncryptDocumentProperties](../../aspose.slides/protectionmanager/encryptdocumentproperties) { get; set; } | Esta propiedad tiene sentido si la presentación está protegida con contraseña. Si es verdadero, las propiedades del documento están encriptadas en el archivo de presentación. Si es falso, las propiedades del documento son públicas mientras la presentación está encriptada. Booleano de lectura/escritura. |
| [EncryptionPassword](../../aspose.slides/protectionmanager/encryptionpassword) { get; } | Obtiene la contraseña que se utiliza para la encriptación de la presentación. String de solo lectura. |
| [IsEncrypted](../../aspose.slides/protectionmanager/isencrypted) { get; } | Obtiene un valor que indica si esta instancia está encriptada. Booleano de solo lectura. |
| [IsOnlyDocumentPropertiesLoaded](../../aspose.slides/protectionmanager/isonlydocumentpropertiesloaded) { get; } | Esta propiedad tiene sentido si el archivo de presentación está protegido con contraseña y las propiedades del documento de este archivo son públicas. Un valor verdadero significa que solo se cargan las propiedades del documento desde un archivo de presentación encriptado sin usar contraseña. Un valor falso significa que se carga toda la presentación encriptada con el uso de la contraseña correcta, no solo se cargan las propiedades del documento. Si la presentación no está encriptada, entonces el valor de la propiedad siempre es falso. Si las propiedades del documento de un archivo encriptado no son públicas, entonces el valor de la propiedad siempre es falso. Si Presentation.EncryptDocumentProperties es verdadero, entonces el valor de la propiedad IsOnlyDocumentPropertiesLoaded siempre es falso. Booleano de solo lectura. |
| [IsWriteProtected](../../aspose.slides/protectionmanager/iswriteprotected) { get; } | Obtiene un valor que indica si esta presentación está protegida contra escritura. Booleano de solo lectura. |
| [ReadOnlyRecommended](../../aspose.slides/protectionmanager/readonlyrecommended) { get; set; } | Obtiene o establece la recomendación de solo lectura. Booleano de lectura/escritura. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CheckWriteProtection](../../aspose.slides/protectionmanager/checkwriteprotection)(string) | Determina si una presentación está protegida por contraseña para modificar. |
| [Encrypt](../../aspose.slides/protectionmanager/encrypt)(string) | Encripta la presentación con la contraseña especificada. |
| [RemoveEncryption](../../aspose.slides/protectionmanager/removeencryption)() | Elimina la encriptación. |
| [RemoveWriteProtection](../../aspose.slides/protectionmanager/removewriteprotection)() | Elimina la protección contra escritura para esta presentación. |
| [SetWriteProtection](../../aspose.slides/protectionmanager/setwriteprotection)(string) | Establece la protección contra escritura para esta presentación con la contraseña especificada. |

### Ver También

* interfaz [IProtectionManager](../iprotectionmanager)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->