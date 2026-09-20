---
title: insert_from_html method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Vytváří snímky z HTML textu a vkládá je do kolekce na určenou pozici.

### Návratová hodnota
Přidané snímky



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice, kam vložit. |
| html_text | **str** | HTML k přidání. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Vytváří snímky z HTML textu a vkládá je do kolekce na určenou pozici.

### Návratová hodnota
Přidané snímky



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice, kam vložit. |
| html_stream | **io.RawIOBase** | Objekt Stream, který bude použit jako zdroj HTML souboru. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Vytváří snímky z HTML textu a vkládá je do kolekce na určenou pozici.

### Návratová hodnota
Přidané snímky



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice, kam vložit. |
| html_text | **str** | HTML k přidání. |
| use_slide_with_index_as_start | **bool** | Toto označení určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem.<br/><br/>            Pokud **true** , pak vložení dat začne na prázdném místě v snímku se zadaným indexem.<br/><br/>            Pokud **false** , data budou přidána do vytvořených snímků. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Vytváří snímky z HTML textu a vkládá je do kolekce na určenou pozici.

### Návratová hodnota
Přidané snímky



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice, kam vložit. |
| html_stream | **io.RawIOBase** | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| use_slide_with_index_as_start | **bool** | Toto označení určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem.<br/><br/>            Pokud **true** , pak vložení dat začne na prázdném místě v snímku se zadaným indexem.<br/><br/>            Pokud **false** , data budou přidána do vytvořených snímků. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Vytváří snímky z HTML textu a vkládá je do kolekce na určenou pozici.

### Návratová hodnota
Přidané snímky.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice, kam vložit. |
| html_text | **str** | HTML k přidání. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver) | Objekt callbacku používaný k načtení externích objektů. Pokud je tento parametr None, všechny externí objekty budou ignorovány. |
| uri | **str** | URI specifikovaného HTML. Použito k rozlišení relativních odkazů. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Vytváří snímky z HTML textu a vkládá je do kolekce na určenou pozici.

### Návratová hodnota
Přidané snímky.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice, kam vložit. |
| html_stream | **io.RawIOBase** | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver) | Objekt callbacku používaný k načtení externích objektů. Pokud je tento parametr None, všechny externí objekty budou ignorovány. |
| uri | **str** | URI specifikovaného HTML. Použito k rozlišení relativních odkazů. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Vytváří snímky z HTML textu a vkládá je do kolekce na určenou pozici.

### Návratová hodnota
Přidané snímky.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice, kam vložit. |
| html_text | **str** | HTML k přidání. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver) | Objekt callbacku používaný k načtení externích objektů. Pokud je tento parametr None, všechny externí objekty budou ignorovány. |
| uri | **str** | URI specifikovaného HTML. Použito k rozlišení relativních odkazů. |
| use_slide_with_index_as_start | **bool** | Toto označení určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem.<br/><br/>            Pokud **true** , pak vložení dat začne na prázdném místě v snímku se zadaným indexem.<br/><br/>            Pokud **false** , data budou přidána do vytvořených snímků. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Vytváří snímky z HTML textu a vkládá je do kolekce na určenou pozici.

### Návratová hodnota
Přidané snímky.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice, kam vložit. |
| html_stream | **io.RawIOBase** | Objekt Stream, který bude použit jako zdroj HTML souboru. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver) | Objekt callbacku používaný k načtení externích objektů. Pokud je tento parametr None, všechny externí objekty budou ignorovány. |
| uri | **str** | URI specifikovaného HTML. Použito k rozlišení relativních odkazů. |
| use_slide_with_index_as_start | **bool** | Toto označení určuje, jak zahájit vkládání: od nového snímku nebo od snímku se zadaným indexem.<br/><br/>            Pokud **true** , pak vložení dat začne na prázdném místě v snímku se zadaným indexem.<br/><br/>            Pokud **false** , data budou přidána do vytvořených snímků. |



### Viz také
* třída [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver)
* třída [`SlideCollection`](/slides/python-net/cs/aspose.slides/slidecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)