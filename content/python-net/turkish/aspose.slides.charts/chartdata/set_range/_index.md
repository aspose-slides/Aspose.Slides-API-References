---
title: set_range method
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Grafik veri aralığını ayarlar. Seriler ve kategoriler yeni veri aralığına göre güncellenecektir.
            Eğer veri aralığındaki seri sayısı grafik verisindeki seri sayısından daha fazla ise, mevcut koleksiyondaki son seriye aynı tipe sahip ek seriler koleksiyonun sonuna eklenecektir.


```python
def set_range(self, formula):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| formula | **str** | The cells data range formula. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula None'dur. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Desteklenmeyen grafik türü |
| **RuntimeError(Proxy error(ArgumentException))** | formula yanlış biçimde. |



### Ayrıca Bakınız
* sınıf [`ChartData`](/slides/python-net/tr/aspose.slides.charts/chartdata)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)