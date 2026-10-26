---
title: add_from_html method
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/slidecollection/add_from_html/
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
| html_text | **str** | HTML do dodania. |


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
| html_stream | **io.RawIOBase** | Obiekt Stream, który będzie używany jako źródło pliku HTML. |


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
| html_text | **str** | HTML do dodania. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest None, wszystkie zewnętrzne obiekty będą ignorowane. |
| uri | **str** | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |


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
| html_stream | **io.RawIOBase** | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania zewnętrznych obiektów. Jeśli ten parametr jest None, wszystkie zewnętrzne obiekty będą ignorowane. |
| uri | **str** | Adres URI określonego HTML. Używany do rozwiązywania względnych odnośników. |



### Zobacz także
* klasa [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver)
* klasa [`SlideCollection`](/slides/python-net/pl/aspose.slides/slidecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)