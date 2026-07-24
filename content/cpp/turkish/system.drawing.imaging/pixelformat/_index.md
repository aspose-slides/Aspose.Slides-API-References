---
title: PixelFormat
second_title: Aspose.Slides için C++ API Referansı
description: Bir pikselin renk veri biçimini belirtir.
type: docs
weight: 326
url: /tr/system.drawing.imaging/pixelformat/
---
## PixelFormat enum

Bir pikselin renk veri biçimini belirtir.

```cpp
enum class PixelFormat
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Indexed | 65536 | Piksel verisinin renk indeksli değerler içerdiğini ve bunun sistem renk tablosundaki renklere bir indeks olduğunu belirtir. |
| Gdi | 131072 | Piksel verisinin GDI renkleri içerdiğini belirtir. |
| Alpha | 262144 | Piksel verisinin önceden çarpılmamış alpha değerleri içerdiğini belirtir. |
| PAlpha | 524288 | Piksel verisinin önceden çarpılmış alpha değerleri içerdiğini belirtir. |
| Extended | 1048576 | Ayrılmış. |
| Canonical | 2097152 | Her piksel için 32 bit, 24 bit renk derinliği ve 8 bit alpha kanalı olan piksel biçimini belirtir. |
| Undefined | 0 | Piksel biçiminin tanımsız olduğunu belirtir. |
| DontCare | 0 | Piksel biçiminin belirtilmediğini gösterir. |
| Format1bppIndexed | n/a | Piksel biçiminin piksel başına 1 bit indeksli renk olduğunu belirtir. |
| Format4bppIndexed | n/a | Piksel biçiminin piksel başına 4 bit indeksli renk olduğunu belirtir. |
| Format8bppIndexed | n/a | Piksel biçiminin piksel başına 8 bit indeksli renk olduğunu belirtir. |
| Format16bppGrayScale | n/a | Piksel biçiminin piksel başına 16 bit olduğunu belirtir. Renk bilgisi 65536 gri tonunu tanımlar. |
| Format16bppRgb555 | n/a | Piksel biçiminin piksel başına 16 bit olduğunu, kırmızı, yeşil ve mavi bileşenlerin her birinin 5 bit olduğunu ve kalan bitin kullanılmadığını belirtir. |
| Format16bppRgb565 | n/a | Piksel biçiminin piksel başına 16 bit olduğunu, kırmızı bileşenin 5 bit, yeşil bileşenin 6 bit ve mavi bileşenin 5 bit olduğunu belirtir. |
| Format16bppArgb1555 | n/a | Piksel biçiminin piksel başına 16 bit olduğunu, kırmızı, yeşil ve mavi bileşenlerin her birinin 5 bit ve alpha için 1 bit olduğunu belirtir. |
| Format24bppRgb | n/a | Piksel biçiminin piksel başına 24 bit olduğunu, kırmızı, yeşil ve mavi bileşenlerin her birinin 8 bit olduğunu belirtir. |
| Format32bppRgb | n/a | Piksel biçiminin piksel başına 32 bit olduğunu, kırmızı, yeşil ve mavi bileşenlerin her birinin 8 bit ve kalan 8 bitin kullanılmadığını belirtir. |
| Format32bppArgb | n/a | Piksel biçiminin piksel başına 32 bit olduğunu, kırmızı, yeşil ve mavi bileşenlerin her birinin 8 bit ve alpha için 8 bit olduğunu belirtir. |
| Format32bppPArgb | n/a | Piksel biçiminin piksel başına 32 bit olduğunu, kırmızı, yeşil ve mavi bileşenlerin her birinin 8 bit ve alpha için 8 bit olduğunu belirtir. Kırmızı, yeşil ve mavi bileşenler alpha bileşeninin değerine göre önceden çarpılmıştır. |
| Format48bppRgb | n/a | Piksel biçiminin piksel başına 48 bit olduğunu, kırmızı, yeşil ve mavi bileşenlerin her birinin 16 bit olduğunu belirtir. |
| Format64bppArgb | n/a | Piksel biçiminin piksel başına 64 bit olduğunu, kırmızı, yeşil ve mavi bileşenlerin her birinin 16 bit ve alpha için 16 bit olduğunu belirtir. |
| Format64bppPArgb | n/a | Piksel biçiminin piksel başına 64 bit olduğunu, kırmızı, yeşil ve mavi bileşenlerin her birinin 16 bit ve alpha için 16 bit olduğunu belirtir. Kırmızı, yeşil ve mavi bileşenler alpha bileşeninin değerine göre önceden çarpılmıştır. |
| Format32bppCMYK | n/a | Piksel biçiminin piksel başına 32 bit olduğunu, cyan, magenta, yellow ve key bileşenlerin her birinin 8 bit olduğunu belirtir. |
| Max | 16 | Bu enum'un maksimum değeri. |

## See Also

* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.Slides](../../)