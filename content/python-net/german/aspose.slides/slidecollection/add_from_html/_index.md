---
title: add_from_html method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

### Rückgabe

Hinzugefügte Folien



```python
def add_from_html(self, html_text):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| html_text | **str** | HTML zum Hinzufügen. |


## add_from_html(self, html_stream) {#iorawiobase}
Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

### Rückgabe

Hinzugefügte Folien



```python
def add_from_html(self, html_stream):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

### Rückgabe

Hinzugefügte Folien.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| html_text | **str** | HTML zum Hinzufügen. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver) | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter None ist, werden alle externen Objekte ignoriert. |
| uri | **str** | Ein URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

### Rückgabe

Hinzugefügte Folien.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver) | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter None ist, werden alle externen Objekte ignoriert. |
| uri | **str** | Ein URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |



### Siehe auch
* Klasse [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver)
* Klasse [`SlideCollection`](/slides/python-net/de/aspose.slides/slidecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)