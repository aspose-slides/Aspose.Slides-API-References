---
title: set_range method
second_title: Aspose.Slides dla Pythona przez .NET API Referencja
description: 
type: docs
url: /pl/aspose.slides.charts/ichartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
Ustaw zakres danych wykresu. Serie i kategorie zostaną zaktualizowane na podstawie nowego zakresu danych.
            Jeśli liczba serii w zakresie danych jest większa niż liczba serii w danych wykresu, zostaną dodane dodatkowe serie o tym samym typie co ostatnia seria w bieżącej kolekcji, umieszczone na końcu kolekcji.

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
| **RuntimeError(Proxy error(ArgumentException))** | formula ma nieprawidłowy format. |

### Zobacz także
* klasa [`IChartData`](/slides/python-net/pl/aspose.slides.charts/ichartdata)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)