---
title: add_from_html method
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Dodaje tekst z podanego ciągu HTML do kolekcji.


```python
def add_from_html(self, text):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| text | **str** | Tekst HTML. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Dodaje tekst z podanego ciągu HTML do kolekcji.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| text | **str** | Tekst HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver) | Obiekt wywołania zwrotnego Resolver, który rozwiązuje URI i pobiera referencjonowane obiekty. |
| uri | **str** | URI dla dodawania dokumentu HTML. Używany do rozwiązywania względnych odnośników. |

### Uwagi

Podanie resolvera może potencjalnie wprowadzić lukę bezpieczeństwa. Należy stosować ostrożnie.



### Zobacz także
* klasa [`IExternalResourceResolver`](/slides/python-net/pl/aspose.slides.importing/iexternalresourceresolver)
* klasa [`ParagraphCollection`](/slides/python-net/pl/aspose.slides/paragraphcollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)