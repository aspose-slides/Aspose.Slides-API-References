---
title: insert_from_html method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

### Returns

Dodane slajdy



```python
def insert_from_html(self, index, html_text):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Pozycja, w której ma zostać wstawiony. |
| html_text | **str** | Html do dodania. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

### Returns

Dodane slajdy



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Pozycja, w której ma zostać wstawiony. |
| html_stream | **io.RawIOBase** | Obiekt Stream, który będzie używany jako źródło pliku HTML. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

### Returns

Dodane slajdy



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Pozycja, w której ma zostać wstawiony. |
| html_text | **str** | Html do dodania. |
| use_slide_with_index_as_start | **bool** | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o określonym indeksie.<br/><br/>            Jeśli **true**, to wstawianie danych rozpocznie się od pustego miejsca na slajdzie o określonym indeksie.<br/><br/>            Jeśli **false**, to dane zostaną dodane do utworzonych slajdów. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

### Returns

Dodane slajdy



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Pozycja, w której ma zostać wstawiony. |
| html_stream | **io.RawIOBase** | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| use_slide_with_index_as_start | **bool** | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o określonym indeksie.<br/><br/>            Jeśli **true**, to wstawianie danych rozpocznie się od pustego miejsca na slajdzie o określonym indeksie.<br/><br/>            Jeśli **false**, to dane zostaną dodane do utworzonych slajdów. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

### Returns

Dodane slajdy.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Pozycja, w której ma zostać wstawiony. |
| html_text | **str** | Html do dodania. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest None, wszystkie zewnętrzne obiekty zostaną zignorowane. |
| uri | **str** | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

### Returns

Dodane slajdy.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Pozycja, w której ma zostać wstawiony. |
| html_stream | **io.RawIOBase** | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest None, wszystkie zewnętrzne obiekty zostaną zignorowane. |
| uri | **str** | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

### Returns

Dodane slajdy.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Pozycja, w której ma zostać wstawiony. |
| html_text | **str** | Html do dodania. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest None, wszystkie zewnętrzne obiekty zostaną zignorowane. |
| uri | **str** | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |
| use_slide_with_index_as_start | **bool** | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o określonym indeksie.<br/><br/>            Jeśli **true**, to wstawianie danych rozpocznie się od pustego miejsca na slajdzie o określonym indeksie.<br/><br/>            Jeśli **false**, to dane zostaną dodane do utworzonych slajdów. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

### Returns

Dodane slajdy.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Pozycja, w której ma zostać wstawiony. |
| html_stream | **io.RawIOBase** | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest None, wszystkie zewnętrzne obiekty zostaną zignorowane. |
| uri | **str** | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |
| use_slide_with_index_as_start | **bool** | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o określonym indeksie.<br/><br/>            Jeśli **true**, to wstawianie danych rozpocznie się od pustego miejsca na slajdzie o określonym indeksie.<br/><br/>            Jeśli **false**, to dane zostaną dodane do utworzonych slajdów. |



### See Also
* klasa [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver)
* klasa [`ISlideCollection`](/slides/python-net/pl/aspose.slides/islidecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)