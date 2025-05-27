---
title: ProtectionManager
second_title: Aspose.Slides para .NET Referencia de API
description: Gestión de la protección con contraseña de presentaciones.
type: docs
weight: 9410
url: /es/aspose.slides/protectionmanager/
---

## Clase ProtectionManager

Gestión de la protección con contraseña de presentaciones.

```csharp
public sealed class ProtectionManager : IProtectionManager
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EncryptDocumentProperties](../../aspose.slides/protectionmanager/encryptdocumentproperties) { get; set; } | Esta propiedad tiene sentido si la presentación está protegida por contraseña. Si es verdadero, entonces las propiedades del documento están cifradas en el archivo de presentación. Si es falso, entonces las propiedades del documento son públicas mientras la presentación está cifrada. Booleano de lectura/escritura. |
| [EncryptionPassword](../../aspose.slides/protectionmanager/encryptionpassword) { get; } | Obtiene la contraseña que se utiliza para el cifrado de la presentación. Cadena de solo lectura. |
| [IsEncrypted](../../aspose.slides/protectionmanager/isencrypted) { get; } | Obtiene un valor que indica si esta instancia está cifrada. Booleano de solo lectura. |
| [IsOnlyDocumentPropertiesLoaded](../../aspose.slides/protectionmanager/isonlydocumentpropertiesloaded) { get; } | Esta propiedad tiene sentido si el archivo de presentación está protegido por contraseña y las propiedades del documento de este archivo son públicas. Un valor de verdadero significa que solo se cargan las propiedades del documento de un archivo de presentación cifrado sin usar la contraseña. Un valor de falso significa que se carga toda la presentación cifrada usando la contraseña correcta, no solo se cargan las propiedades del documento. Si la presentación no está cifrada, el valor de la propiedad siempre es falso. Si las propiedades del documento de un archivo cifrado no son públicas, entonces el valor de la propiedad siempre es falso. Si Presentation.EncryptDocumentProperties es verdadero, entonces el valor de la propiedad IsOnlyDocumentPropertiesLoaded siempre es falso. Booleano de solo lectura. |
| [IsWriteProtected](../../aspose.slides/protectionmanager/iswriteprotected) { get; } | Obtiene un valor que indica si esta presentación está protegida contra escritura. Booleano de solo lectura. |
| [ReadOnlyRecommended](../../aspose.slides/protectionmanager/readonlyrecommended) { get; set; } | Obtiene o establece la recomendación de solo lectura. Booleano de lectura/escritura. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CheckWriteProtection](../../aspose.slides/protectionmanager/checkwriteprotection)(string) | Determina si una presentación está protegida por contraseña para modificar. |
| [Encrypt](../../aspose.slides/protectionmanager/encrypt)(string) | Cifra la presentación con la contraseña especificada. |
| [RemoveEncryption](../../aspose.slides/protectionmanager/removeencryption)() | Elimina el cifrado. |
| [RemoveWriteProtection](../../aspose.slides/protectionmanager/removewriteprotection)() | Elimina la protección contra escritura para esta presentación. |
| [SetWriteProtection](../../aspose.slides/protectionmanager/setwriteprotection)(string) | Establece la protección contra escritura para esta presentación con la contraseña especificada. |

### Véase También

* interfaz [IProtectionManager](../iprotectionmanager)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->