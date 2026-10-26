---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Belirli bir **System.Array** indeksinden başlayarak **System.Collections.Generic.ICollection`1** öğelerini bir **System.Array**'ye kopyalar.

```python
def copy_to(self, array, array_index):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| array | **List[IPortion]** | **System.Array**'nin tek boyutlu hâli, **System.Collections.Generic.ICollection`1**'den kopyalanan öğelerin hedefidir. **System.Array** sıfır tabanlı indekslemeye sahip olmalıdır. |
| array_index | **int** | `array` içinde kopyalamanın başladığı sıfır tabanlı indeks. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` None'dur. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` 0'dan küçüktür. |
| **RuntimeError(Proxy error(ArgumentException))** | Kaynak **System.Collections.Generic.ICollection`1** içindeki öğe sayısı, hedef `array`'in sonuna kadar `array_index` konumundan itibaren mevcut alandan daha fazladır. |

### Ayrıca Bakınız
* sınıf [`PortionCollection`](/slides/python-net/tr/aspose.slides/portioncollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)