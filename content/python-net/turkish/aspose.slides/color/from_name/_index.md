---
title: from_name method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Belirtilen önceden tanımlı renk adından bir renk oluşturur.<br/>Arama büyük/küçük harfe duyarsızdır ve alt çizgileri ile boşlukları yok sayar: `"LightBlue"`, `"lightblue"` ve `"light_blue"` hepsi `Color.light_blue` değerine çözülür. Önceden tanımlı renklerin listesi için [`Color`](/slides/python-net/tr/aspose.slides/color) sınıf sayfasına bakın.

### Dönüş

Adlandırılmış renk.

```python
@staticmethod
def from_name(name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | **str** | Önceden tanımlı bir rengin adı olan bir dizedir. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **ValueError** | Ad, önceden tanımlı bir renk adı değildir. |
| **TypeError** | Ad bir dize değildir. |

### Ayrıca Bakınız
* sınıf [`Color`](/slides/python-net/tr/aspose.slides/color)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)