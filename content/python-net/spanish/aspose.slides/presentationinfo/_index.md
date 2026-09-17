---
title: PresentationInfo class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/presentationinfo/
---
## PresentationInfo clase

Información sobre el archivo de presentación

El tipo PresentationInfo expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`is_encrypted`](/slides/python-net/es/aspose.slides/presentationinfo/is_encrypted/) | Obtiene True si la presentación vinculada está encriptada, de lo contrario False.<br/>            Solo lectura **bool**. |
| [`is_password_protected`](/slides/python-net/es/aspose.slides/presentationinfo/is_password_protected/) | Obtiene un valor que indica si la presentación vinculada está protegida por una contraseña para abrir. |
| [`is_write_protected`](/slides/python-net/es/aspose.slides/presentationinfo/is_write_protected/) | Obtiene un valor que indica si la presentación vinculada está protegida contra escritura. |
| [`load_format`](/slides/python-net/es/aspose.slides/presentationinfo/load_format/) | Obtiene el formato de la presentación vinculada.<br/>            Solo lectura [`LoadFormat`](/slides/python-net/es/aspose.slides/loadformat). |

## Métodos

| Método | Descripción |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/es/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | Escribe la presentación vinculada a un flujo. |
| [`write_binded_presentation(self, file)`](/slides/python-net/es/aspose.slides/presentationinfo/write_binded_presentation/#str) | Escribe la presentación vinculada a un archivo. |
| [`check_password(self, password)`](/slides/python-net/es/aspose.slides/presentationinfo/check_password/#str) | Comprueba si una contraseña es correcta para una presentación protegida con contraseña de apertura. |
| [`check_write_protection(self, password)`](/slides/python-net/es/aspose.slides/presentationinfo/check_write_protection/#str) | Comprueba si una contraseña de modificación es correcta para una presentación protegida contra escritura. |
| [`read_document_properties(self)`](/slides/python-net/es/aspose.slides/presentationinfo/read_document_properties/#) | Obtiene las propiedades del documento de la presentación vinculada. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/es/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | Actualiza las propiedades de la presentación vinculada. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)