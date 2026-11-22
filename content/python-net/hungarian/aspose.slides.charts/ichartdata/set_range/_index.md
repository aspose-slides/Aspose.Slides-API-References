---
title: set_range method
second_title: Aspose.Slides for Python via .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
Beállítja a diagram adat-tartományt. A sorozatok és kategóriák frissülnek az új adat-tartomány alapján.
            Ha az adat-tartományban lévő sorozatok száma nagyobb, mint a diagram adatában lévő sorozatok száma, akkor további sorozatok kerülnek hozzáadásra a gyűjtemény végéhez, amelyek típusa megegyezik a jelenlegi gyűjtemény utolsó sorozatával.

```python
def set_range(self, formula):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| formula | **str** | A cellák adat-tartomány képlete. Például: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | a formula None. |
| **RuntimeError(Proxy error(ArgumentException))** | a formula helytelen formátumú. |

### Lásd még
* osztály [`IChartData`](/slides/python-net/hu/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)