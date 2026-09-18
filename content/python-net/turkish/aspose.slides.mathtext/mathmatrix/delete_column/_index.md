---
title: delete_column method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Belirtilen sütunu siler


```python
def delete_column(self, column_index):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| column_index | **int** | Silinecek sütunun sıfır tabanlı dizini. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Matristeki son tek sütunu silmeye çalıştığınızda |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | columnIndex sıfırdan küçük veya ColumnCount'e eşit ya da daha büyükse |



### Ayrıca Bakınız
* sınıf [`MathMatrix`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)