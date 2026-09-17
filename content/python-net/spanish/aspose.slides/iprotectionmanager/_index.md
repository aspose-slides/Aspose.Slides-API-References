---
title: IProtectionManager class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/iprotectionmanager/
---
## IProtectionManager clase

Gestión de la protección con contraseña de la presentación.

El tipo IProtectionManager expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/es/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Esta propiedad tiene sentido si la presentación está protegida con contraseña.<br/>            Si es true entonces las propiedades del documento están cifradas en el archivo de la presentación.<br/>            Si es false entonces las propiedades del documento son públicas mientras la presentación está cifrada.<br/>            Lectura/escritura **bool**. |
| [`is_encrypted`](/slides/python-net/es/aspose.slides/iprotectionmanager/is_encrypted/) | Obtiene un valor que indica si esta instancia está cifrada.<br/>            Solo lectura **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/es/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Esta propiedad tiene sentido si el archivo de la presentación está protegido con contraseña y las propiedades del documento de este archivo son públicas.<br/>            El valor true significa que solo se cargan las propiedades del documento desde un archivo de presentación cifrado sin usar contraseña.<br/>            El valor false significa que se carga toda la presentación cifrada usando la contraseña correcta, no solo se cargan las propiedades del documento.<br/>            Si la presentación no está cifrada, el valor de la propiedad es siempre false.<br/>            Si las propiedades del documento de un archivo cifrado no son públicas, el valor de la propiedad es siempre false.<br/>            Si PresentationEx.EncryptDocumentProperties es true, entonces el valor de la propiedad IsOnlyDocumentPropertiesLoaded es siempre false.<br/>            Solo lectura **bool**. |
| [`is_write_protected`](/slides/python-net/es/aspose.slides/iprotectionmanager/is_write_protected/) | Obtiene un valor que indica si esta presentación tiene protección de escritura.<br/>            Solo lectura **bool**. |
| [`encryption_password`](/slides/python-net/es/aspose.slides/iprotectionmanager/encryption_password/) | Devuelve la contraseña de cifrado.<br/>            Solo lectura **str**. |
| [`read_only_recommended`](/slides/python-net/es/aspose.slides/iprotectionmanager/read_only_recommended/) | Obtiene o establece la recomendación de solo lectura.<br/>            Lectura/escritura **bool**. |

## Métodos

| Method | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/es/aspose.slides/iprotectionmanager/encrypt/#str) | Cifra la Presentación con la contraseña especificada. |
| [`remove_encryption(self)`](/slides/python-net/es/aspose.slides/iprotectionmanager/remove_encryption/#) | Elimina el cifrado. |
| [`set_write_protection(self, password)`](/slides/python-net/es/aspose.slides/iprotectionmanager/set_write_protection/#str) | Establece protección de escritura para esta presentación con la contraseña especificada. |
| [`remove_write_protection(self)`](/slides/python-net/es/aspose.slides/iprotectionmanager/remove_write_protection/#) | Elimina la protección de escritura para esta presentación. |
| [`check_write_protection(self, password)`](/slides/python-net/es/aspose.slides/iprotectionmanager/check_write_protection/#str) | Determina si una presentación está protegida con contraseña para modificar. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)