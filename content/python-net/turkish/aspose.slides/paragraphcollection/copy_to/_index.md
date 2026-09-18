---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
Belirli bir **System.Array** dizininde başlayarak, **System.Collections.Generic.ICollection`1** öğelerini bir **System.Array**'a kopyalar.


```python
def copy_to(self, array, array_index):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| array | **List[IParagraph]** | Kopyalanan öğelerin hedefi olan tek boyutlu **System.Array**. **System.Array**, **System.Collections.Generic.ICollection`1**'den kopyalanan öğelerin hedefidir. **System.Array**, sıfır tabanlı indeksleme kullanmalıdır. |
| array_index | **int** | `array` içinde kopyalamanın başladığı sıfır tabanlı indeks. |


### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` None'dur. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` 0'dan küçüktür. |
| **RuntimeError(Proxy error(ArgumentException))** | Kaynak **System.Collections.Generic.ICollection`1** içindeki öğe sayısı, `array_index`'den hedef `array`'in sonuna kadar mevcut boş alandan daha fazladır. |



### Ayrıca Bakınız
* sınıf [`ParagraphCollection`](/slides/python-net/tr/aspose.slides/paragraphcollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)