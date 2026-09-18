---
title: add_from_html method
second_title: Aspose.Slides for Python via .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja hozzá.

### Visszatérési érték

Hozzáadott diák



```python
def add_from_html(self, html_text):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| html_text | **str** | A hozzáadandó HTML. |


## add_from_html(self, html_stream) {#iorawiobase}
Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja hozzá.

### Visszatérési érték

Hozzáadott diák



```python
def add_from_html(self, html_stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Egy Stream objektum, amely a HTML fájl forrásaként szolgál. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja hozzá.

### Visszatérési érték

Hozzáadott diák.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| html_text | **str** | A hozzáadandó HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Egy visszahívási objektum külső objektumok lekérésére. Ha ez a paraméter None, akkor az összes külső objektum figyelmen kívül lesz hagyva. |
| uri | **str** | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használható. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Létrehozza a diákat HTML szövegből, és a gyűjtemény végéhez adja hozzá.

### Visszatérési érték

Hozzáadott diák.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Egy Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Egy visszahívási objektum külső objektumok lekérésére. Ha ez a paraméter None, akkor az összes külső objektum figyelmen kívül lesz hagyva. |
| uri | **str** | A megadott HTML URI-ja. Relatív hivatkozások feloldásához használható. |



### Lásd még
* osztály [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver)
* osztály [`SlideCollection`](/slides/python-net/hu/aspose.slides/slidecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)