---
title: delete_row method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Belirtilen satırı siler


```python
def delete_row(self, row_index):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| row_index | **int** | Silinecek satırın sıfır tabanlı dizini. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Matrisin son tek satırını silmeye çalıştığınızda |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | rowIndex sıfırdan küçük veya RowCount'e eşit ya da büyük ise |



### Diğerlerine Bakın
* sınıf [`MathMatrix`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)