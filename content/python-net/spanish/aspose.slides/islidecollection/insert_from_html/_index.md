---
title: insert_from_html method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición para insertar. |
| html_text | **str** | Html a agregar. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición para insertar. |
| html_stream | **io.RawIOBase** | Un objeto Stream que será usado como fuente de un archivo HTML. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición para insertar. |
| html_text | **str** | Html a agregar. |
| use_slide_with_index_as_start | **bool** | Esta bandera determina cómo iniciar la inserción: desde una nueva diapositiva o desde la diapositiva con el índice especificado.<br/><br/>            Si **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>            Si **false** , then data will be added to the created slides. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición para insertar. |
| html_stream | **io.RawIOBase** | Un objeto Stream que será usado como fuente de un archivo HTML. |
| use_slide_with_index_as_start | **bool** | Esta bandera determina cómo iniciar la inserción: desde una nueva diapositiva o desde la diapositiva con el índice especificado.<br/><br/>            Si **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>            Si **false** , then data will be added to the created slides. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición para insertar. |
| html_text | **str** | Html a agregar. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver) | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es None, todos los objetos externos serán ignorados. |
| uri | **str** | Un URI del HTML especificado. Usado para resolver enlaces relativos. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición para insertar. |
| html_stream | **io.RawIOBase** | Un objeto Stream que será usado como fuente de un archivo HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver) | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es None, todos los objetos externos serán ignorados. |
| uri | **str** | Un URI del HTML especificado. Usado para resolver enlaces relativos. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición para insertar. |
| html_text | **str** | Html a agregar. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver) | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es None, todos los objetos externos serán ignorados. |
| uri | **str** | Un URI del HTML especificado. Usado para resolver enlaces relativos. |
| use_slide_with_index_as_start | **bool** | Esta bandera determina cómo iniciar la inserción: desde una nueva diapositiva o desde la diapositiva con el índice especificado.<br/><br/>            Si **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>            Si **false** , then data will be added to the created slides. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición para insertar. |
| html_stream | **io.RawIOBase** | Un objeto Stream que será usado como fuente de un archivo HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver) | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es None, todos los objetos externos serán ignorados. |
| uri | **str** | Un URI del HTML especificado. Usado para resolver enlaces relativos. |
| use_slide_with_index_as_start | **bool** | Esta bandera determina cómo iniciar la inserción: desde una nueva diapositiva o desde la diapositiva con el índice especificado.<br/><br/>            Si **true** , then data insertion will start from an empty space on the slide with the specified index.<br/><br/>            Si **false** , then data will be added to the created slides. |



### Ver también
* clase [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver)
* clase [`ISlideCollection`](/slides/python-net/es/aspose.slides/islidecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)