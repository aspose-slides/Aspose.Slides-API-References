---
title: set_range method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Grafik veri aralığını ayarlayın. Seriler ve kategoriler yeni veri aralığına göre güncellenecektir.
            Eğer veri aralığındaki seri sayısı grafik verisindeki seri sayısından fazla ise, mevcut koleksiyondaki son serinin aynı türünde ek seriler koleksiyonun sonuna eklenecektir.


```python
def set_range(self, formula):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| formula | **str** | Hücrelerin veri aralığı formülü. Örneğin: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula None'dır. |
| **RuntimeError(Proxy error(ArgumentException))** | formula hatalı bir formata sahiptir. |



### İlgili
* sınıf [`IChartData`](/slides/python-net/tr/aspose.slides.charts/ichartdata)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)