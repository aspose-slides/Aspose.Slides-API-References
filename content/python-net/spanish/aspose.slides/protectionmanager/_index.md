---
title: ProtectionManager class
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/protectionmanager/
---
## ProtectionManager clase

Gestión de la protección con contraseña de la presentación.

El tipo ProtectionManager expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/es/aspose.slides/protectionmanager/encrypt_document_properties/) | Esta propiedad tiene sentido, si la presentación está protegida con contraseña.<br/>            Si es true entonces las propiedades del documento están cifradas en el archivo de presentación.<br/>            Si es false entonces las propiedades del documento son públicas mientras la presentación está cifrada.<br/>            Lectura/escritura **bool**. |
| [`is_encrypted`](/slides/python-net/es/aspose.slides/protectionmanager/is_encrypted/) | Obtiene un valor que indica si esta instancia está cifrada.<br/>            Solo lectura **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/es/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Esta propiedad tiene sentido, si el archivo de presentación está protegido con contraseña y las propiedades del documento de este archivo son públicas.<br/>            Un valor true indica que solo se cargan las propiedades del documento desde un archivo de presentación cifrado sin usar la contraseña.<br/>            Un valor false indica que se carga toda la presentación cifrada usando la contraseña correcta, no solo se cargan las propiedades del documento.<br/>            Si la presentación no está cifrada, el valor de la propiedad es siempre false.<br/>            Si las propiedades del documento de un archivo cifrado no son públicas, el valor de la propiedad es siempre false.<br/>            Si Presentation.EncryptDocumentProperties es true, entonces IsOnlyDocumentPropertiesLoaded <br/>            property value es siempre false.<br/>            Solo lectura **bool**. |
| [`is_write_protected`](/slides/python-net/es/aspose.slides/protectionmanager/is_write_protected/) | Obtiene un valor que indica si esta presentación está protegida contra escritura.<br/>            Solo lectura **bool**. |
| [`encryption_password`](/slides/python-net/es/aspose.slides/protectionmanager/encryption_password/) | Obtiene la contraseña que se utiliza para el cifrado de la presentación.<br/>            Solo lectura **str**. |
| [`read_only_recommended`](/slides/python-net/es/aspose.slides/protectionmanager/read_only_recommended/) | Obtiene o establece la recomendación de solo lectura.<br/>            Lectura/escritura **bool**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/es/aspose.slides/protectionmanager/encrypt/#str) | Cifra la presentación con la contraseña especificada. |
| [`remove_encryption(self)`](/slides/python-net/es/aspose.slides/protectionmanager/remove_encryption/#) | Elimina el cifrado. |
| [`set_write_protection(self, password)`](/slides/python-net/es/aspose.slides/protectionmanager/set_write_protection/#str) | Establece protección contra escritura para esta presentación con la contraseña especificada. |
| [`remove_write_protection(self)`](/slides/python-net/es/aspose.slides/protectionmanager/remove_write_protection/#) | Elimina la protección contra escritura de esta presentación. |
| [`check_write_protection(self, password)`](/slides/python-net/es/aspose.slides/protectionmanager/check_write_protection/#str) | Determina si una presentación está protegida con contraseña para modificarla. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)