---
title: set_range method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Állítsa be a diagram adat-tartományát. A sorozatok és kategóriák az új adat-tartomány alapján frissülnek.
            Ha az adat-tartományban lévő sorozatok száma nagyobb, mint a diagram adatában szereplő sorozatok száma, akkor további sorozatok, amelyek típusa
            megegyezik az aktuális gyűjtemény utolsó sorozatával, hozzá lesznek adva a gyűjtemény végéhez.


```python
def set_range(self, formula):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| formula | **str** | A cellák adat-tartományának képlete. Pl.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula None értékű. |
| **RuntimeError(Proxy error(ArgumentException))** | formula helytelen formátumú. |



### Lásd még
* osztály [`IChartData`](/slides/python-net/hu/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)