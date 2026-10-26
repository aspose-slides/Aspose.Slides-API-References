---
title: insert_from_html method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

### Retour

Toegevoegde dia's



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Positie om in te voegen. |
| html_text | **str** | HTML om toe te voegen. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

### Retour

Toegevoegde dia's



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Positie om in te voegen. |
| html_stream | **io.RawIOBase** | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

### Retour

Toegevoegde dia's



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Positie om in te voegen. |
| html_text | **str** | HTML om toe te voegen. |
| use_slide_with_index_as_start | **bool** | Deze vlag bepaalt hoe de invoeging wordt gestart: vanaf een nieuwe dia of vanaf de dia met de opgegeven index.<br/><br/>            Als **true**, dan start de gegevensinvoer vanaf een lege ruimte op de dia met de opgegeven index.<br/><br/>            Als **false**, dan worden de gegevens toegevoegd aan de aangemaakte dia's. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

### Retour

Toegevoegde dia's



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Positie om in te voegen. |
| html_stream | **io.RawIOBase** | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| use_slide_with_index_as_start | **bool** | Deze vlag bepaalt hoe de invoeging wordt gestart: vanaf een nieuwe dia of vanaf de dia met de opgegeven index.<br/><br/>            Als **true**, dan start de gegevensinvoer vanaf een lege ruimte op de dia met de opgegeven index.<br/><br/>            Als **false**, dan worden de gegevens toegevoegd aan de aangemaakte dia's. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

### Retour

Toegevoegde dia's.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Positie om in te voegen. |
| html_text | **str** | HTML om toe te voegen. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/nl/aspose.slides.importing/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter None is, worden alle externe objecten genegeerd. |
| uri | **str** | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

### Retour

Toegevoegde dia's.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Positie om in te voegen. |
| html_stream | **io.RawIOBase** | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/nl/aspose.slides.importing/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter None is, worden alle externe objecten genegeerd. |
| uri | **str** | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

### Retour

Toegevoegde dia's.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Positie om in te voegen. |
| html_text | **str** | HTML om toe te voegen. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/nl/aspose.slides.importing/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter None is, worden alle externe objecten genegeerd. |
| uri | **str** | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |
| use_slide_with_index_as_start | **bool** | Deze vlag bepaalt hoe de invoeging wordt gestart: vanaf een nieuwe dia of vanaf de dia met de opgegeven index.<br/><br/>            Als **true**, dan start de gegevensinvoer vanaf een lege ruimte op de dia met de opgegeven index.<br/><br/>            Als **false**, dan worden de gegevens toegevoegd aan de aangemaakte dia's. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Maakt dia's van HTML-tekst en voegt ze toe aan de collectie op de opgegeven positie.

### Retour

Toegevoegde dia's.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Positie om in te voegen. |
| html_stream | **io.RawIOBase** | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/nl/aspose.slides.importing/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter None is, worden alle externe objecten genegeerd. |
| uri | **str** | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve koppelingen op te lossen. |
| use_slide_with_index_as_start | **bool** | Deze vlag bepaalt hoe de invoeging wordt gestart: vanaf een nieuwe dia of vanaf de dia met de opgegeven index.<br/><br/>            Als **true**, dan start de gegevensinvoer vanaf een lege ruimte op de dia met de opgegeven index.<br/><br/>            Als **false**, dan worden de gegevens toegevoegd aan de aangemaakte dia's. |



### Zie ook
* klasse [`IExternalResourceResolver`](/slides/python-net/nl/aspose.slides.importing/iexternalresourceresolver)
* klasse [`ISlideCollection`](/slides/python-net/nl/aspose.slides/islidecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)