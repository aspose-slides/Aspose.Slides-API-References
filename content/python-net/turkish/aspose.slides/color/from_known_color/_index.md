---
title: from_known_color method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Belirtilen önceden tanımlı renkten bir renk oluşturur.<br/>Bu, bir sistem rengi elde etmenin tek yoludur (örneğin `KnownColor.CONTROL`): sistem renkleri, değerleri masaüstü temasına bağlı olduğundan `Color` öznitelikleri olarak sunulmaz, bu yüzden kitaplık çalışma zamanından okunur.

### Döndürülen Değer
Bu yöntemin oluşturduğu renk.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| known_color | **KnownColor** | `KnownColor` özetlemesi ( .NET `System.Drawing.KnownColor`'ı yansıtan bir `IntEnum`) öğesi ya da onun tamsayı değeri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **ValueError** | Değer geçerli bir `KnownColor` üyesi değildir. |



### Ayrıca Bakınız
* sınıf [`Color`](/slides/python-net/tr/aspose.slides/color)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)