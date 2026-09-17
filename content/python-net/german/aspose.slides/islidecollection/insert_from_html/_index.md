---
title: insert_from_html method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

### Rückgabe

Hinzugefügte Folien



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Position zum Einfügen. |
| html_text | **str** | HTML zum Hinzufügen. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

### Rückgabe

Hinzugefügte Folien



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Position zum Einfügen. |
| html_stream | **io.RawIOBase** | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

### Rückgabe

Hinzugefügte Folien



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Position zum Einfügen. |
| html_text | **str** | HTML zum Hinzufügen. |
| use_slide_with_index_as_start | **bool** | Dieses Flag bestimmt, wie das Einfügen gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index.<br/><br/>            Wenn **true** ist, beginnt das Einfügen der Daten von einem leeren Bereich auf der Folie mit dem angegebenen Index.<br/><br/>            Wenn **false** ist, werden die Daten zu den erstellten Folien hinzugefügt. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

### Rückgabe

Hinzugefügte Folien



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Position zum Einfügen. |
| html_stream | **io.RawIOBase** | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| use_slide_with_index_as_start | **bool** | Dieses Flag bestimmt, wie das Einfügen gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index.<br/><br/>            Wenn **true** ist, beginnt das Einfügen der Daten von einem leeren Bereich auf der Folie mit dem angegebenen Index.<br/><br/>            Wenn **false** ist, werden die Daten zu den erstellten Folien hinzugefügt. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

### Rückgabe

Hinzugefügte Folien.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Position zum Einfügen. |
| html_text | **str** | HTML zum Hinzufügen. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver) | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter None ist, werden alle externen Objekte ignoriert. |
| uri | **str** | Ein URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

### Rückgabe

Hinzugefügte Folien.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Position zum Einfügen. |
| html_stream | **io.RawIOBase** | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver) | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter None ist, werden alle externen Objekte ignoriert. |
| uri | **str** | Ein URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

### Rückgabe

Hinzugefügte Folien.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Position zum Einfügen. |
| html_text | **str** | HTML zum Hinzufügen. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver) | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter None ist, werden alle externen Objekte ignoriert. |
| uri | **str** | Ein URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |
| use_slide_with_index_as_start | **bool** | Dieses Flag bestimmt, wie das Einfügen gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index.<br/><br/>            Wenn **true** ist, beginnt das Einfügen der Daten von einem leeren Bereich auf der Folie mit dem angegebenen Index.<br/><br/>            Wenn **false** ist, werden die Daten zu den erstellten Folien hinzugefügt. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

### Rückgabe

Hinzugefügte Folien.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Position zum Einfügen. |
| html_stream | **io.RawIOBase** | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver) | Ein Callback-Objekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter None ist, werden alle externen Objekte ignoriert. |
| uri | **str** | Ein URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |
| use_slide_with_index_as_start | **bool** | Dieses Flag bestimmt, wie das Einfügen gestartet wird: von einer neuen Folie oder von der Folie mit dem angegebenen Index.<br/><br/>            Wenn **true** ist, beginnt das Einfügen der Daten von einem leeren Bereich auf der Folie mit dem angegebenen Index.<br/><br/>            Wenn **false** ist, werden die Daten zu den erstellten Folien hinzugefügt. |



### Siehe auch
* Klasse [`IExternalResourceResolver`](/slides/python-net/de/aspose.slides.importing/iexternalresourceresolver)
* Klasse [`ISlideCollection`](/slides/python-net/de/aspose.slides/islidecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)