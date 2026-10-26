---
title: add_from_html method
second_title: Aspose.Slides dla Pythona via .NET - dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Dodaje tekst z określonego łańcucha HTML do kolekcji.


```python
def add_from_html(self, text):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| text | **str** | tekst HTML. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Dodaje tekst z określonego łańcucha HTML do kolekcji.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| text | **str** | tekst HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver) | Obiekt wywołania zwrotnego rozwiązującego, który rozwiązuje URI i pobiera odwołane obiekty. |
| uri | **str** | URI do dodania dokumentu HTML. Używane do rozwiązywania względnych odnośników. |

### Uwagi

Określenie resolver może potencjalnie wprowadzić podatność. Używaj ostrożnie.



### Zobacz także
* klasa [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver)
* klasa [`IParagraphCollection`](/slides/python-net/pl/aspose.slides/iparagraphcollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)