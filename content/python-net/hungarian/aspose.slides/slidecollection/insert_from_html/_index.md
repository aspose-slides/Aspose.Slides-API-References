---
title: insert_from_html method
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Létrehozza a diáket HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe.

### Visszatérési érték

Hozzáadott diák



```python
def insert_from_html(self, index, html_text):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Beszúrás pozíciója. |
| html_text | **str** | Hozzáadandó HTML. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Létrehozza a diáket HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe.

### Visszatérési érték

Hozzáadott diák



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Beszúrás pozíciója. |
| html_stream | **io.RawIOBase** | Egy Stream objektum, amely a HTML fájl forrásaként szolgál. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Létrehozza a diáket HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe.

### Visszatérési érték

Hozzáadott diák



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Beszúrás pozíciója. |
| html_text | **str** | Hozzáadandó HTML. |
| use_slide_with_index_as_start | **bool** | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diától vagy a megadott indexű diától.<br/><br/>            Ha **true** , akkor az adatok beszúrása az adott indexű dián egy üres térből indul.<br/><br/>            Ha **false** , akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Létrehozza a diáket HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe.

### Visszatérési érték

Hozzáadott diák



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Beszúrás pozíciója. |
| html_stream | **io.RawIOBase** | Egy Stream objektum, amely a HTML fájl forrásaként szolgál. |
| use_slide_with_index_as_start | **bool** | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diától vagy a megadott indexű diától.<br/><br/>            Ha **true** , akkor az adatok beszúrása az adott indexű dián egy üres térből indul.<br/><br/>            Ha **false** , akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Létrehozza a diáket HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe.

### Visszatérési érték

Hozzáadott diák.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Beszúrás pozíciója. |
| html_text | **str** | Hozzáadott HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter None, akkor az összes külső objektum figyelmen kívül lesz hagyva. |
| uri | **str** | Az adott HTML URI-ja. Relatív hivatkozások feloldására szolgál. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Létrehozza a diáket HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe.

### Visszatérési érték

Hozzáadott diák.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Beszúrás pozíciója. |
| html_stream | **io.RawIOBase** | Egy Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter None, akkor az összes külső objektum figyelmen kívül lesz hagyva. |
| uri | **str** | Az adott HTML URI-ja. Relatív hivatkozások feloldására szolgál. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Létrehozza a diáket HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe.

### Visszatérési érték

Hozzáadott diák.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Beszúrás pozíciója. |
| html_text | **str** | Hozzáadott HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter None, akkor az összes külső objektum figyelmen kívül lesz hagyva. |
| uri | **str** | Az adott HTML URI-ja. Relatív hivatkozások feloldására szolgál. |
| use_slide_with_index_as_start | **bool** | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diától vagy a megadott indexű diától.<br/><br/>            Ha **true** , akkor az adatok beszúrása az adott indexű dián egy üres térből indul.<br/><br/>            Ha **false** , akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Létrehozza a diáket HTML szövegből, és a megadott pozícióba illeszti a gyűjteménybe.

### Visszatérési érték

Hozzáadott diák.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Beszúrás pozíciója. |
| html_stream | **io.RawIOBase** | Egy Stream objektum, amely a HTML fájl forrásaként szolgál. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Egy visszahívási objektum, amely külső objektumok lekérésére szolgál. Ha ez a paraméter None, akkor az összes külső objektum figyelmen kívül lesz hagyva. |
| uri | **str** | Az adott HTML URI-ja. Relatív hivatkozások feloldására szolgál. |
| use_slide_with_index_as_start | **bool** | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diától vagy a megadott indexű diától.<br/><br/>            Ha **true** , akkor az adatok beszúrása az adott indexű dián egy üres térből indul.<br/><br/>            Ha **false** , akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |



### Lásd még
* osztály [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver)
* osztály [`SlideCollection`](/slides/python-net/hu/aspose.slides/slidecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)