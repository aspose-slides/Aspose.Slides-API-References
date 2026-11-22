---
title: set_range method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
Set chart data range. Series and categories will be updated based on new data range.
            If amount of series in data range greater than count of series in the chart data then additional series with the same type
            as a last series in the current collection will be added to the end of the collection.

```python
def set_range(self, formula):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| formula | **str** | Hücre veri aralığı formülü. Örneğin: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula None'dur. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Desteklenmeyen grafik türü |
| **RuntimeError(Proxy error(ArgumentException))** | formula hatalı formata sahip. |

### İlgili
* sınıf [`ChartData`](/slides/python-net/tr/aspose.slides.charts/chartdata)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)