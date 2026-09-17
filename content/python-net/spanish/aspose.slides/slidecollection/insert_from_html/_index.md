---
title: insert_from_html method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición donde insertar. |
| html_text | **str** | HTML a añadir. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición donde insertar. |
| html_stream | **io.RawIOBase** | Un objeto Stream que se utilizará como fuente de un archivo HTML. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición donde insertar. |
| html_text | **str** | HTML a añadir. |
| use_slide_with_index_as_start | **bool** | Este indicador determina cómo iniciar la inserción: desde una diapositiva nueva o desde la diapositiva con el índice especificado.<br/><br/>            Si **true**, entonces la inserción de datos comenzará en un espacio vacío de la diapositiva con el índice especificado.<br/><br/>            Si **false**, entonces los datos se añadirán a las diapositivas creadas. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición donde insertar. |
| html_stream | **io.RawIOBase** | Un objeto Stream que se utilizará como fuente de un archivo HTML. |
| use_slide_with_index_as_start | **bool** | Este indicador determina cómo iniciar la inserción: desde una diapositiva nueva o desde la diapositiva con el índice especificado.<br/><br/>            Si **true**, entonces la inserción de datos comenzará en un espacio vacío de la diapositiva con el índice especificado.<br/><br/>            Si **false**, entonces los datos se añadirán a las diapositivas creadas. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición donde insertar. |
| html_text | **str** | HTML a añadir. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver) | Un objeto de devolución de llamada utilizado para obtener objetos externos. Si este parámetro es None, todos los objetos externos serán ignorados. |
| uri | **str** | Un URI del HTML especificado. Utilizado para resolver enlaces relativos. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición donde insertar. |
| html_stream | **io.RawIOBase** | Un objeto Stream que se utilizará como fuente de un archivo HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver) | Un objeto de devolución de llamada utilizado para obtener objetos externos. Si este parámetro es None, todos los objetos externos serán ignorados. |
| uri | **str** | Un URI del HTML especificado. Utilizado para resolver enlaces relativos. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición donde insertar. |
| html_text | **str** | HTML a añadir. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver) | Un objeto de devolución de llamada utilizado para obtener objetos externos. Si este parámetro es None, todos los objetos externos serán ignorados. |
| uri | **str** | Un URI del HTML especificado. Utilizado para resolver enlaces relativos. |
| use_slide_with_index_as_start | **bool** | Este indicador determina cómo iniciar la inserción: desde una diapositiva nueva o desde la diapositiva con el índice especificado.<br/><br/>            Si **true**, entonces la inserción de datos comenzará en un espacio vacío de la diapositiva con el índice especificado.<br/><br/>            Si **false**, entonces los datos se añadirán a las diapositivas creadas. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Crea diapositivas a partir de texto HTML e inserta las diapositivas en la colección en la posición especificada.

### Devuelve

Diapositivas añadidas.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Posición donde insertar. |
| html_stream | **io.RawIOBase** | Un objeto Stream que se utilizará como fuente de un archivo HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver) | Un objeto de devolución de llamada utilizado para obtener objetos externos. Si este parámetro es None, todos los objetos externos serán ignorados. |
| uri | **str** | Un URI del HTML especificado. Utilizado para resolver enlaces relativos. |
| use_slide_with_index_as_start | **bool** | Este indicador determina cómo iniciar la inserción: desde una diapositiva nueva o desde la diapositiva con el índice especificado.<br/><br/>            Si **true**, entonces la inserción de datos comenzará en un espacio vacío de la diapositiva con el índice especificado.<br/><br/>            Si **false**, entonces los datos se añadirán a las diapositivas creadas. |



### Ver también
* clase [`IExternalResourceResolver`](/slides/python-net/es/aspose.slides.importing/iexternalresourceresolver)
* clase [`SlideCollection`](/slides/python-net/es/aspose.slides/slidecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)