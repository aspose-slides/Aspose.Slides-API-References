---
title: from_name method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Vytvoří barvu ze zadaného názvu předdefinované barvy.<br/>Vyhledávání není citlivé na velikost písmen a ignoruje podtržítka i mezery: `"LightBlue"`, `"lightblue"` a `"light_blue"` všechny odkazují na `Color.light_blue`. Viz stránka třídy [`Color`](/slides/python-net/cs/aspose.slides/color) pro seznam předdefinovaných barev.

### Návratová hodnota

Pojmenovaná barva.



```python
@staticmethod
def from_name(name):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| name | **str** | Řetězec, který je názvem předdefinované barvy. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **ValueError** | Název není názvem předdefinované barvy. |
| **TypeError** | Název není řetězec. |



### Viz také
* třída [`Color`](/slides/python-net/cs/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)