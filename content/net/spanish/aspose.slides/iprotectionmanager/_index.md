---
title: IProtectionManager
second_title: Referencia de API de Aspose.Slides para .NET
description: Gestión de protección de contraseña de presentación.
type: docs
weight: 6620
url: /es/aspose.slides/iprotectionmanager/
---

## Interfaz IProtectionManager

Gestión de protección de contraseña de presentación.

```csharp
public interface IProtectionManager
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EncryptDocumentProperties](../../aspose.slides/iprotectionmanager/encryptdocumentproperties) { get; set; } | Esta propiedad tiene sentido si la presentación está protegida por contraseña. Si es verdadero, las propiedades del documento están encriptadas en el archivo de presentación. Si es falso, las propiedades del documento son públicas mientras la presentación esté encriptada. Booleano de lectura/escritura. |
| [EncryptionPassword](../../aspose.slides/iprotectionmanager/encryptionpassword) { get; } | Devuelve la contraseña de encriptación. Cadena de solo lectura. |
| [IsEncrypted](../../aspose.slides/iprotectionmanager/isencrypted) { get; } | Obtiene un valor que indica si esta instancia está encriptada. Booleano de solo lectura. |
| [IsOnlyDocumentPropertiesLoaded](../../aspose.slides/iprotectionmanager/isonlydocumentpropertiesloaded) { get; } | Esta propiedad tiene sentido si el archivo de presentación está protegido por contraseña y las propiedades del documento de este archivo son públicas. Un valor verdadero significa que solo se cargan las propiedades del documento desde un archivo de presentación encriptado sin usar la contraseña. Un valor falso significa que se carga toda la presentación encriptada con el uso de la contraseña correcta, no solo las propiedades del documento. Si la presentación no está encriptada, entonces el valor de la propiedad siempre es falso. Si las propiedades del documento de un archivo encriptado no son públicas, entonces el valor de la propiedad siempre es falso. Si PresentationEx.EncryptDocumentProperties es verdadero, entonces el valor de la propiedad IsOnlyDocumentPropertiesLoaded es siempre falso. Booleano de solo lectura. |
| [IsWriteProtected](../../aspose.slides/iprotectionmanager/iswriteprotected) { get; } | Obtiene un valor que indica si esta presentación está protegida contra escritura. Booleano de solo lectura. |
| [ReadOnlyRecommended](../../aspose.slides/iprotectionmanager/readonlyrecommended) { get; set; } | Obtiene o establece la recomendación de solo lectura. Booleano de lectura/escritura. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CheckWriteProtection](../../aspose.slides/iprotectionmanager/checkwriteprotection)(string) | Determina si una presentación está protegida por contraseña para modificar. |
| [Encrypt](../../aspose.slides/iprotectionmanager/encrypt)(string) | Encripta la presentación con la contraseña especificada. |
| [RemoveEncryption](../../aspose.slides/iprotectionmanager/removeencryption)() | Elimina la encriptación. |
| [RemoveWriteProtection](../../aspose.slides/iprotectionmanager/removewriteprotection)() | Elimina la protección contra escritura de esta presentación. |
| [SetWriteProtection](../../aspose.slides/iprotectionmanager/setwriteprotection)(string) | Establece la protección contra escritura de esta presentación con la contraseña especificada. |

### Vea también

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->