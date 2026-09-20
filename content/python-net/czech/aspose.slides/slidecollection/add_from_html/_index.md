---
title: add_from_html method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Vytvoří snímky z HTML textu a přidá je na konec kolekce.

### Návratová hodnota

Přidané snímky



```python
def add_from_html(self, html_text):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| html_text | **str** | HTML ke přidání. |


## add_from_html(self, html_stream) {#iorawiobase}
Vytvoří snímky z HTML textu a přidá je na konec kolekce.

### Návratová hodnota

Přidané snímky



```python
def add_from_html(self, html_stream):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Objekt Stream, který bude použit jako zdroj HTML souboru. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Vytvoří snímky z HTML textu a přidá je na konec kolekce.

### Návratová hodnota

Přidané snímky.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| html_text | **str** | HTML ke přidání. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver) | Objekt zpětného volání používaný k načítání externích objektů. Pokud je tento parametr None, všechny externí objekty budou ignorovány. |
| uri | **str** | URI určeného HTML. Používá se k řešení relativních odkazů. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Vytvoří snímky z HTML textu a přidá je na konec kolekce.

### Návratová hodnota

Přidané snímky.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver) | Objekt zpětného volání používaný k načítání externích objektů. Pokud je tento parametr None, všechny externí objekty budou ignorovány. |
| uri | **str** | URI určeného HTML. Používá se k řešení relativních odkazů. |



### Viz také
* třída [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver)
* třída [`SlideCollection`](/slides/python-net/cs/aspose.slides/slidecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)