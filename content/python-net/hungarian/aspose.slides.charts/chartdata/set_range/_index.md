---
title: set_range method
second_title: Aspose.Slides for Python .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Állítsa be a diagram adatlagot. A sorozatok és kategóriák az új adatlag alapján frissülnek.
            Ha az adatlagban lévő sorozatok száma nagyobb, mint a diagram adatában lévő sorozatok száma, akkor további sorozatok kerülnek hozzáadásra a gyűjtemény végéhez, amelyek típusa megegyezik az aktuális gyűjtemény utolsó sorozatának típusával.


```python
def set_range(self, formula):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| formula | **str** | A cellák adatlag képlete. Például: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | a formula None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Nem támogatott diagramtípus |
| **RuntimeError(Proxy error(ArgumentException))** | a formula helytelen formátumú. |



### Lásd még
* osztály [`ChartData`](/slides/python-net/hu/aspose.slides.charts/chartdata)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)