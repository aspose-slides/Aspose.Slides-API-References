---
title: set_range method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Nastavit rozsah dat grafu. Řady a kategorie budou aktualizovány na základě nového rozsahu dat.
            Pokud je počet řad v rozsahu dat větší než počet řad v datech grafu, budou přidány další řady se stejným typem jako poslední řada v aktuální kolekci na konec kolekce.


```python
def set_range(self, formula):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| formula | **str** | Vzorec rozsahu dat buněk. Např.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula je None. |
| **RuntimeError(Proxy error(ArgumentException))** | formula má nesprávný formát. |



### Viz také
* třída [`IChartData`](/slides/python-net/cs/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)