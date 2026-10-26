---
title: insert_from_html method
second_title: Aspose.Slides pro Python pomocí .NET API reference
description: 
type: docs
url: /cs/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

### Návratová hodnota

Přidané snímky



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice pro vložení. |
| html_text | **str** | HTML ke přidání. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

### Návratová hodnota

Přidané snímky



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice pro vložení. |
| html_stream | **io.RawIOBase** | Objekt Stream, který bude použit jako zdroj souboru HTML. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

### Návratová hodnota

Přidané snímky



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice pro vložení. |
| html_text | **str** | HTML ke přidání. |
| use_slide_with_index_as_start | **bool** | Toto označení určuje, jak začít vkládání: od nového snímku nebo od snímku se zadaným indexem.<br/><br/>            Pokud **true** , pak vkládání dat začne na prázdném prostoru na snímku se zadaným indexem.<br/><br/>            Pokud **false** , pak budou data přidána do vytvořených snímků. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

### Návratová hodnota

Přidané snímky



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice pro vložení. |
| html_stream | **io.RawIOBase** | Objekt Stream, který bude použit jako zdroj souboru HTML. |
| use_slide_with_index_as_start | **bool** | Toto označení určuje, jak začít vkládání: od nového snímku nebo od snímku se zadaným indexem.<br/><br/>            Pokud **true** , pak vkládání dat začne na prázdném prostoru na snímku se zadaným indexem.<br/><br/>            Pokud **false** , pak budou data přidána do vytvořených snímků. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

### Návratová hodnota

Přidané snímky.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice pro vložení. |
| html_text | **str** | HTML ke přidání. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver) | Objekt zpětného volání používaný k získání externích objektů. Pokud je tento parametr None, budou všechny externí objekty ignorovány. |
| uri | **str** | URI zadaného HTML. Používá se k řešení relativních odkazů. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

### Návratová hodnota

Přidané snímky.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice pro vložení. |
| html_stream | **io.RawIOBase** | Objekt Stream, který bude použit jako zdroj souboru HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver) | Objekt zpětného volání používaný k získání externích objektů. Pokud je tento parametr None, budou všechny externí objekty ignorovány. |
| uri | **str** | URI zadaného HTML. Používá se k řešení relativních odkazů. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

### Návratová hodnota

Přidané snímky.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice pro vložení. |
| html_text | **str** | HTML ke přidání. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver) | Objekt zpětného volání používaný k získání externích objektů. Pokud je tento parametr None, budou všechny externí objekty ignorovány. |
| uri | **str** | URI zadaného HTML. Používá se k řešení relativních odkazů. |
| use_slide_with_index_as_start | **bool** | Toto označení určuje, jak začít vkládání: od nového snímku nebo od snímku se zadaným indexem.<br/><br/>            Pokud **true** , pak vkládání dat začne na prázdném prostoru na snímku se zadaným indexem.<br/><br/>            Pokud **false** , pak budou data přidána do vytvořených snímků. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

### Návratová hodnota

Přidané snímky.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Pozice pro vložení. |
| html_stream | **io.RawIOBase** | Objekt Stream, který bude použit jako zdroj souboru HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver) | Objekt zpětného volání používaný k získání externích objektů. Pokud je tento parametr None, budou všechny externí objekty ignorovány. |
| uri | **str** | URI zadaného HTML. Používá se k řešení relativních odkazů. |
| use_slide_with_index_as_start | **bool** | Toto označení určuje, jak začít vkládání: od nového snímku nebo od snímku se zadaným indexem.<br/><br/>            Pokud **true** , pak vkládání dat začne na prázdném prostoru na snímku se zadaným indexem.<br/><br/>            Pokud **false** , pak budou data přidána do vytvořených snímků. |



### Viz také
* třída [`IExternalResourceResolver`](/slides/python-net/cs/aspose.slides.importing/iexternalresourceresolver)
* třída [`ISlideCollection`](/slides/python-net/cs/aspose.slides/islidecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)