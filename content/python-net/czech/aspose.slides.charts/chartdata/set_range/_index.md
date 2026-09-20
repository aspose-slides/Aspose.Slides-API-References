---
title: set_range method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Nastaví rozsah dat grafu. Řady a kategorie budou aktualizovány na základě nového rozsahu dat.
            Pokud je počet řad v rozsahu dat větší než počet řad v datech grafu, pak budou přidány další řady se stejným typem
            jako poslední řada v aktuální kolekci, budou přidány na konec kolekce.


```python
def set_range(self, formula):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| formula | **str** | Vzorec rozsahu dat buněk. Např: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula je None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Nepodporovaný typ grafu |
| **RuntimeError(Proxy error(ArgumentException))** | formula má nesprávný formát. |



### Viz také
* třída [`ChartData`](/slides/python-net/cs/aspose.slides.charts/chartdata)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)