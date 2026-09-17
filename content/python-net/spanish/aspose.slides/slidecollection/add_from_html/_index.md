---
title: add_from_html method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

### Devuelve

Diapositivas añadidas



```python
def add_from_html(self, html_text):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| html_text | **str** | HTML a agregar. |


## add_from_html(self, html_stream) {#iorawiobase}
Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

### Devuelve

Diapositivas añadidas



```python
def add_from_html(self, html_stream):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Un objeto Stream que se usará como fuente de un archivo HTML. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

### Devuelve

Diapositivas añadidas.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| html_text | **str** | HTML a agregar. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver) | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es None se ignorarán todos los objetos externos. |
| uri | **str** | Un URI del HTML especificado. Se usa para resolver enlaces relativos. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Crea diapositivas a partir de texto HTML y las agrega al final de la colección.

### Devuelve

Diapositivas añadidas.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Un objeto Stream que se usará como fuente de un archivo HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver) | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es None se ignorarán todos los objetos externos. |
| uri | **str** | Un URI del HTML especificado. Se usa para resolver enlaces relativos. |



### Ver también
* clase [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver)
* clase [`SlideCollection`](/slides/python-net/es/aspose.slides/slidecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)