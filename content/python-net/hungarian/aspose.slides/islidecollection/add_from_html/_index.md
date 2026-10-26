---
title: add_from_html method
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/islidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá.

### Returns

Hozzáadott diák



```python
def add_from_html(self, html_text):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| html_text | **str** | Hozzáadandó HTML. |


## add_from_html(self, html_stream) {#iorawiobase}
Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá.

### Returns

Hozzáadott diák



```python
def add_from_html(self, html_stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Egy Stream objektum, amely a HTML fájl forrásaként szolgál. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá.

### Returns

Hozzáadott diák.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| html_text | **str** | Hozzáadandó HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Egy callback objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter None, akkor minden külső objektum figyelmen kívül lesz hagyva. |
| uri | **str** | Az adott HTML URI-ja. Relatív hivatkozások feloldására használható. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Diákat hoz létre HTML szövegből, és a gyűjtemény végére adja hozzá.

### Returns

Hozzáadott diák.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Egy Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Egy callback objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter None, akkor minden külső objektum figyelmen kívül lesz hagyva. |
| uri | **str** | Az adott HTML URI-ja. Relatív hivatkozások feloldására használható. |



### See Also
* osztály [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver)
* osztály [`ISlideCollection`](/slides/python-net/hu/aspose.slides/islidecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)