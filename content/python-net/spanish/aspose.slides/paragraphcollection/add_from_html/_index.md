---
title: add_from_html method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Agrega texto desde la cadena html especificada a la colección.

```python
def add_from_html(self, text):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | **str** | texto HTML. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Agrega texto desde la cadena html especificada a la colección.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | **str** | texto HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver) | Objeto de devolución de llamada resolver que resuelve URIs y obtiene los objetos referenciados. |
| uri | **str** | URI para agregar el documento HTML. Usado para resolver enlaces relativos. |

### Observaciones

Especificar resolver puede introducir potencialmente una vulnerabilidad. Úselo con precaución.

### Ver también
* clase [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver)
* clase [`ParagraphCollection`](/slides/python-net/es/aspose.slides/paragraphcollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)