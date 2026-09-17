---
title: add_from_html method
second_title: Referencia de API Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/islidecollection/add_from_html/
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
| html_text | **str** | HTML a añadir. |


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
| html_stream | **io.RawIOBase** | Un objeto Stream que se utilizará como origen de un archivo HTML. |


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
| html_text | **str** | HTML a añadir. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver) | Un objeto de devolución de llamada utilizado para obtener objetos externos. Si este parámetro es None, todos los objetos externos serán ignorados. |
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
| html_stream | **io.RawIOBase** | Un objeto Stream que se utilizará como origen de un archivo HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver) | Un objeto de devolución de llamada utilizado para obtener objetos externos. Si este parámetro es None, todos los objetos externos serán ignorados. |
| uri | **str** | Un URI del HTML especificado. Se usa para resolver enlaces relativos. |



### Ver también
* clase [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver)
* clase [`ISlideCollection`](/slides/python-net/es/aspose.slides/islidecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)