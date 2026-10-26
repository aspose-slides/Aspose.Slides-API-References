---
title: insert_from_html method
second_title: Aspose.Slides Pythonhoz a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott helyen.

### Visszatérési érték

Hozzáadott diák



```python
def insert_from_html(self, index, html_text):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A beszúrás helye. |
| html_text | **str** | Hozzáadandó HTML. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott helyen.

### Visszatérési érték

Hozzáadott diák



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A beszúrás helye. |
| html_stream | **io.RawIOBase** | A Stream objektum, amely HTML fájl forrásaként szolgál. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott helyen.

### Visszatérési érték

Hozzáadott diák



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A beszúrás helye. |
| html_text | **str** | Hozzáadott HTML. |
| use_slide_with_index_as_start | **bool** | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diárról vagy a megadott indexű diáról.<br/><br/>            Ha **true**, akkor az adatbeszúrás egy üres helyről kezdődik a megadott indexű dián.<br/><br/>            Ha **false**, akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott helyen.

### Visszatérési érték

Hozzáadott diák



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A beszúrás helye. |
| html_stream | **io.RawIOBase** | A Stream objektum, amely HTML fájl forrásaként szolgál. |
| use_slide_with_index_as_start | **bool** | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diárról vagy a megadott indexű diáról.<br/><br/>            Ha **true**, akkor az adatbeszúrás egy üres helyről kezdődik a megadott indexű dián.<br/><br/>            Ha **false**, akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott helyen.

### Visszatérési érték

Hozzáadott diák.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A beszúrás helye. |
| html_text | **str** | Hozzáadott HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Egy visszahívási objektum külső objektumok lekéréséhez. Ha ez a paraméter None, minden külső objektum figyelmen kívül lesz hagyva. |
| uri | **str** | Az adott HTML URI-ja. Relatív hivatkozások feloldásához használható. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott helyen.

### Visszatérési érték

Hozzáadott diák.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A beszúrás helye. |
| html_stream | **io.RawIOBase** | A Stream objektum, amely HTML fájl forrásaként szolgál. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Egy visszahívási objektum külső objektumok lekéréséhez. Ha ez a paraméter None, minden külső objektum figyelmen kívül lesz hagyva. |
| uri | **str** | Az adott HTML URI-ja. Relatív hivatkozások feloldásához használható. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott helyen.

### Visszatérési érték

Hozzáadott diák.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A beszúrás helye. |
| html_text | **str** | Hozzáadott HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Egy visszahívási objektum külső objektumok lekéréséhez. Ha ez a paraméter None, minden külső objektum figyelmen kívül lesz hagyva. |
| uri | **str** | Az adott HTML URI-ja. Relatív hivatkozások feloldásához használható. |
| use_slide_with_index_as_start | **bool** | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diárról vagy a megadott indexű diáról.<br/><br/>            Ha **true**, akkor az adatbeszúrás egy üres helyről kezdődik a megadott indexű dián.<br/><br/>            Ha **false**, akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Diákat hoz létre HTML szövegből, és beszúrja őket a gyűjteménybe a megadott helyen.

### Visszatérési érték

Hozzáadott diák.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A beszúrás helye. |
| html_stream | **io.RawIOBase** | A Stream objektum, amely HTML fájl forrásaként szolgál. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver) | Egy visszahívási objektum külső objektumok lekéréséhez. Ha ez a paraméter None, minden külső objektum figyelmen kívül lesz hagyva. |
| uri | **str** | Az adott HTML URI-ja. Relatív hivatkozások feloldásához használható. |
| use_slide_with_index_as_start | **bool** | Ez a jelző határozza meg, hogyan kezdődjön a beszúrás: új diárról vagy a megadott indexű diáról.<br/><br/>            Ha **true**, akkor az adatbeszúrás egy üres helyről kezdődik a megadott indexű dián.<br/><br/>            Ha **false**, akkor az adatok a létrehozott diákhoz lesznek hozzáadva. |



### Lásd még
* osztály [`IExternalResourceResolver`](/slides/python-net/hu/aspose.slides.importing/iexternalresourceresolver)
* osztály [`ISlideCollection`](/slides/python-net/hu/aspose.slides/islidecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)