---
title: ExternalResourceResolver class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver clase

Clase de devolución de llamada utilizada para resolver recursos externos durante la importación de documentos Html, Svg.
Usar este resolvedor podría crear una vulnerabilidad cuando un archivo HTML o SVG proporcionado por el cliente haga que el software del servidor obtenga un archivo local o de red. Úselo con precaución. Se recomienda no especificar ExternalResourceResolver en absoluto (solo se leerán los objetos incrustados) o crear alguna subclase que verifique si el uri especificado es válido.

El tipo ExternalResourceResolver expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/es/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Resuelve el URI absoluto a partir de los URIs base y relativo. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/es/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Mapea un URI a un objeto que contiene el recurso real. |

### Ver también
* módulo [`aspose.slides.importing`](/slides/python-net/es/aspose.slides.importing)
* biblioteca [`Aspose.Slides`](/slides/python-net)