---
title: HtmlExternalResolver class
second_title: Aspose.Slides para Python a través de la referencia de API .NET
description: 
type: docs
url: /es/aspose.slides.importing/htmlexternalresolver/
---
## Clase HtmlExternalResolver

Objeto de devolución de llamada utilizado por la rutina de importación HTML para obtener objetos referenciados como imágenes. Usar este resolvedor podría crear una vulnerabilidad cuando un archivo HTML proporcionado por el cliente haga que el software del servidor obtenga un archivo local o de red. Úselo con precaución. Se recomienda no especificar HtmlExternalResolver en absoluto (solo se leerán los objetos incrustados) o crear alguna subclase que verifique si el URI especificado es válido.

El tipo HtmlExternalResolver expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/es/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Resuelve el URI absoluto a partir de los URIs base y relativo. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/es/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Asocia un URI a un objeto que contiene el recurso real. |

### Ver también
* módulo [`aspose.slides.importing`](/slides/python-net/es/aspose.slides.importing)
* biblioteca [`Aspose.Slides`](/slides/python-net)