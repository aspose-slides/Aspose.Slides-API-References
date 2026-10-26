---
title: name property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/color/name/
weight: 190
---
## name vlastnost
Získá název této barvy.<br/>            Pro pojmenovanou barvu (pojmenovanou konstantu, jako je `Color.red`, nebo barvu vytvořenou pomocí [`from_name`](/slides/python-net/cs/aspose.slides/color/from_name/)) se vrací název .NET, např. `"Red"` nebo `"LightBlue"`.<br/>            Pro jakoukoli jinou barvu se vrací hodnota ARGB jako hexadecimální řetězec v malých písmenech bez nulového doplnění, např. `"ffff0000"`. `Color.empty.name` je `"0"`.
            Pouze pro čtení **str**.

### Definice:
```python
@property
def name(self):
    ...
```


### Viz také
* třída [`Color`](/slides/python-net/cs/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)