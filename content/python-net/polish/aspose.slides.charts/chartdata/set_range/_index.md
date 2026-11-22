---
title: set_range method
second_title: Aspose.Slides dla Pythona przez .NET - Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/chartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
Ustaw zakres danych wykresu. Series i kategorie zostaną zaktualizowane na podstawie nowego zakresu danych.
Jeśli liczba series w data range jest większa niż liczba series w chart data, dodatkowe series o tym samym typie co ostatnia series w bieżącej kolekcji zostaną dodane na koniec kolekcji.


```python
def set_range(self, formula):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| formula | **str** | Formuła zakresu danych komórek. Np: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula jest None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Unsupported chart type |
| **RuntimeError(Proxy error(ArgumentException))** | formula ma niepoprawny format. |



### Zobacz także
* klasa [`ChartData`](/slides/python-net/pl/aspose.slides.charts/chartdata)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)