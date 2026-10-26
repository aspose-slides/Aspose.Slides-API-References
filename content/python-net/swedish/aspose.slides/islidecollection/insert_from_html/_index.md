---
title: insert_from_html method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

### Returnerar

Tillagda bilder



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Position att infoga. |
| html_text | **str** | Html att lägga till. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

### Returnerar

Tillagda bilder



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Position att infoga. |
| html_stream | **io.RawIOBase** | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

### Returnerar

Tillagda bilder



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Position att infoga. |
| html_text | **str** | Html att lägga till. |
| use_slide_with_index_as_start | **bool** | Denna flagga bestämmer hur infogningen ska påbörjas: från en ny bild eller från bilden med det angivna indexet.<br/><br/>            Om **true** startar datainföringen från ett tomt utrymme på bilden med det angivna indexet.<br/><br/>            Om **false** läggs data till de skapade bilderna. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

### Returnerar

Tillagda bilder



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Position att infoga. |
| html_stream | **io.RawIOBase** | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| use_slide_with_index_as_start | **bool** | Denna flagga bestämmer hur infogningen ska påbörjas: från en ny bild eller från bilden med det angivna indexet.<br/><br/>            Om **true** startar datainföringen från ett tomt utrymme på bilden med det angivna indexet.<br/><br/>            Om **false** läggs data till de skapade bilderna. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

### Returnerar

Tillagda bilder.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Position att infoga. |
| html_text | **str** | Html att lägga till. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/sv/aspose.slides.importing/iexternalresourceresolver) | Ett återuppringnings-objekt som används för att hämta externa objekt. Om detta parameter är None ignoreras alla externa objekt. |
| uri | **str** | En URI för den angivna HTML. Används för att lösa relativa länkar. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

### Returnerar

Tillagda bilder.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Position att infoga. |
| html_stream | **io.RawIOBase** | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/sv/aspose.slides.importing/iexternalresourceresolver) | Ett återuppringnings-objekt som används för att hämta externa objekt. Om detta parameter är None ignoreras alla externa objekt. |
| uri | **str** | En URI för den angivna HTML. Används för att lösa relativa länkar. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

### Returnerar

Tillagda bilder.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Position att infoga. |
| html_text | **str** | Html att lägga till. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/sv/aspose.slides.importing/iexternalresourceresolver) | Ett återuppringnings-objekt som används för att hämta externa objekt. Om detta parameter är None ignoreras alla externa objekt. |
| uri | **str** | En URI för den angivna HTML. Används för att lösa relativa länkar. |
| use_slide_with_index_as_start | **bool** | Denna flagga bestämmer hur infogningen ska påbörjas: från en ny bild eller från bilden med det angivna indexet.<br/><br/>            Om **true** startar datainföringen från ett tomt utrymme på bilden med det angivna indexet.<br/><br/>            Om **false** läggs data till de skapade bilderna. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

### Returnerar

Tillagda bilder.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Position att infoga. |
| html_stream | **io.RawIOBase** | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/sv/aspose.slides.importing/iexternalresourceresolver) | Ett återuppringnings-objekt som används för att hämta externa objekt. Om detta parameter är None ignoreras alla externa objekt. |
| uri | **str** | En URI för den angivna HTML. Används för att lösa relativa länkar. |
| use_slide_with_index_as_start | **bool** | Denna flagga bestämmer hur infogningen ska påbörjas: från en ny bild eller från bilden med det angivna indexet.<br/><br/>            Om **true** startar datainföringen från ett tomt utrymme på bilden med det angivna indexet.<br/><br/>            Om **false** läggs data till de skapade bilderna. |



### Se även
* klass [`IExternalResourceResolver`](/slides/python-net/sv/aspose.slides.importing/iexternalresourceresolver)
* klass [`ISlideCollection`](/slides/python-net/sv/aspose.slides/islidecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)