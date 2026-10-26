---
title: Hyperlink constructor
second_title: Odwołanie do API Aspose.Slides dla Pythona przez .NET
description: 
type: docs
url: /pl/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Tworzy instancję hiperłącza.


```python
def __init__(self, url):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| url | **str** | Adres URL hiperłącza. |


## __init__(self, slide) {#islide}
Tworzy instancję hiperłącza, które wskazuje na konkretny slajd.  
Uwaga: utworzone hiperłącze powinno być przypisane do jakiegoś obiektu z tej samej prezentacji, w przeciwnym razie link zostanie zapisany jako NoAction.


```python
def __init__(self, slide):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | Docelowy slajd. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Tworzy instancję hiperłącza przy użyciu innego hiperłącza jako źródła, nadpisując właściwości dodatkowe.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/pl/aspose.slides/hyperlink) | Źródłowe hiperłącze |
| target_frame | **str** | Docelowa ramka |
| tooltip | **str** | Tekst podpowiedzi |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### Zobacz także
* klasa [`Hyperlink`](/slides/python-net/pl/aspose.slides/hyperlink)
* klasa [`ISlide`](/slides/python-net/pl/aspose.slides/islide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)