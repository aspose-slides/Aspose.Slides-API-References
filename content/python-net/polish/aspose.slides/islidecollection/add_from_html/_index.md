---
title: add_from_html method
second_title: Aspose.Slides dla Pythona – .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/islidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

### Zwraca

Dodane slajdy



```python
def add_from_html(self, html_text):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| html_text | **str** | Html to add. |


## add_from_html(self, html_stream) {#iorawiobase}
Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

### Zwraca

Dodane slajdy



```python
def add_from_html(self, html_stream):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | A Stream object which will be used as a source of a HTML file. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

### Zwraca

Dodane slajdy.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| html_text | **str** | Html to add. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is None all external objects will be ignored. |
| uri | **str** | An URI of the specified HTML. Used to resolve relative links. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

### Zwraca

Dodane slajdy.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | A Stream object which will be used as a source of a HTML file. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is None all external objects will be ignored. |
| uri | **str** | An URI of the specified HTML. Used to resolve relative links. |



### Zobacz również
* klasa [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver)
* klasa [`ISlideCollection`](/slides/python-net/pl/aspose.slides/islidecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)