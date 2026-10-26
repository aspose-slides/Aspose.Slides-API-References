---
title: add_from_html method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

### Returnerar

Tillagda bilder



```python
def add_from_html(self, html_text):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| html_text | **str** | HTML att lägga till. |


## add_from_html(self, html_stream) {#iorawiobase}
Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

### Returnerar

Tillagda bilder



```python
def add_from_html(self, html_stream):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

### Returnerar

Tillagda bilder.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| html_text | **str** | HTML att lägga till. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/sv/aspose.slides.importing/iexternalresourceresolver) | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är None ignoreras alla externa objekt. |
| uri | **str** | En URI för den specificerade HTML-en. Används för att lösa relativa länkar. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

### Returnerar

Tillagda bilder.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/sv/aspose.slides.importing/iexternalresourceresolver) | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är None ignoreras alla externa objekt. |
| uri | **str** | En URI för den specificerade HTML-en. Används för att lösa relativa länkar. |



### Se också
* klass [`IExternalResourceResolver`](/slides/python-net/sv/aspose.slides.importing/iexternalresourceresolver)
* klass [`SlideCollection`](/slides/python-net/sv/aspose.slides/slidecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)