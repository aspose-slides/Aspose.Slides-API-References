---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
**System.Collections.Generic.ICollection`1**'den bir **System.Array**'e öğeleri kopyalar, belirli bir **System.Array** indeksinde başlar.

```python
def copy_to(self, array, array_index):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| array | **List[IBehavior]** | Kopyalanan öğelerin hedefi olan tek boyutlu **System.Array**. **System.Array** sıfır tabanlı indekslemeye sahip olmalıdır. |
| array_index | **int** | `array` içinde kopyalamanın başlayacağı sıfır tabanlı indeks. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` None'dur. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` 0'dan küçüktür. |
| **RuntimeError(Proxy error(ArgumentException))** | Kaynak **System.Collections.Generic.ICollection`1**'deki öğe sayısı, hedef `array`'de `array_index`'den itibaren kalan kullanılabilir alandan daha fazladır. |

### Ayrıca
* sınıf [`BehaviorCollection`](/slides/python-net/tr/aspose.slides.animation/behaviorcollection)
* modül [`aspose.slides.animation`](/slides/python-net/tr/aspose.slides.animation)
* kütüphane [`Aspose.Slides`](/slides/python-net)