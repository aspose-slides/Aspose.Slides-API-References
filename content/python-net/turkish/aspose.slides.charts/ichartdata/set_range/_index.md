---
title: set_range method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
Grafik veri aralığını ayarlayın. Seriler ve kategoriler yeni veri aralığına göre güncellenecektir.
            Eğer veri aralığındaki seri sayısı, grafik verisindeki seri sayısından fazla ise, mevcut koleksiyondaki son seriye aynı tipe sahip ek seriler koleksiyonun sonuna eklenecektir.


```python
def set_range(self, formula):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| formula | **str** | Hücrelerin veri aralığı formülü. Örn: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formül None'dır. |
| **RuntimeError(Proxy error(ArgumentException))** | formül yanlış biçimde. |



### Bakınız
* sınıf [`IChartData`](/slides/python-net/tr/aspose.slides.charts/ichartdata)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)