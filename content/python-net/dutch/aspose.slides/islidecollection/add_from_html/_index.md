---
title: add_from_html method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/islidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

### Retour

Toegevoegde dia's



```python
def add_from_html(self, html_text):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| html_text | **str** | Html om toe te voegen. |


## add_from_html(self, html_stream) {#iorawiobase}
Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

### Retour

Toegevoegde dia's



```python
def add_from_html(self, html_stream):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

### Retour

Toegevoegde dia's.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| html_text | **str** | Html om toe te voegen. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/nl/aspose.slides.importing/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter None is, worden alle externe objecten genegeerd. |
| uri | **str** | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve links op te lossen. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

### Retour

Toegevoegde dia's.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/nl/aspose.slides.importing/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter None is, worden alle externe objecten genegeerd. |
| uri | **str** | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve links op te lossen. |



### Zie ook
* klasse [`IExternalResourceResolver`](/slides/python-net/nl/aspose.slides.importing/iexternalresourceresolver)
* klasse [`ISlideCollection`](/slides/python-net/nl/aspose.slides/islidecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)