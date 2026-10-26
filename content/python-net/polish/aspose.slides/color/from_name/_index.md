---
title: from_name method
second_title: Aspose.Slides dla Pythona przez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Tworzy kolor na podstawie określonej nazwy predefiniowanego koloru.<br/>Wyszukiwanie jest nieczułe na wielkość liter i ignoruje podkreślenia oraz spacje: `"LightBlue"`, `"lightblue"` i `"light_blue"` wszystkie zwracają `Color.light_blue`. Zobacz stronę klasy [`Color`](/slides/python-net/pl/aspose.slides/color) aby uzyskać listę predefiniowanych kolorów.

### Zwraca

Nazwany kolor.



```python
@staticmethod
def from_name(name):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| name | **str** | Ciąg znaków będący nazwą predefiniowanego koloru. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **ValueError** | Nazwa nie jest nazwą predefiniowanego koloru. |
| **TypeError** | Nazwa nie jest ciągiem znaków. |



### Zobacz także
* klasa [`Color`](/slides/python-net/pl/aspose.slides/color)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)