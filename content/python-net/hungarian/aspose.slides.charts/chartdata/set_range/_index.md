---
title: set_range method
second_title: Aspose.Slides Python számára .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
Állítsa be a diagram adatcímkét. Az adatsorok és kategóriák az új adatcímke alapján frissülnek.
            Ha az adatcímkén belüli sorozatok száma nagyobb, mint a diagram adatában lévő sorozatok száma, akkor további sorozatok a ugyanazzal a típussal
            mint az aktuális gyűjtemény utolsó sorozata, a gyűjtemény végéhez lesznek hozzáadva.


```python
def set_range(self, formula):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| formula | **str** | A cellák adatcímke képlete. Például: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | a formula értéke None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Nem támogatott diagramtípus |
| **RuntimeError(Proxy error(ArgumentException))** | a formula formátuma helytelen. |



### Lásd még
* osztály [`ChartData`](/slides/python-net/hu/aspose.slides.charts/chartdata)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)