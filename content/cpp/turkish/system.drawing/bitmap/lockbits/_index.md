---
title: LockBits()
second_title: Aspose.Slides için C++ API Referansı
description: Bir Bitmap'i sistem belleğine kilitler.
type: docs
weight: 118
url: /tr/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) method

[Bitmap](../)'yi sistem belleğine kilitler.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Kilitlenecek görüntünün bölgesini belirten bir dikdörtgen |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | bitmap'e erişim seviyesini belirtir |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Bu bitmap'in veri biçimi |

### Dönüş Değeri

Perform edilen kilitleme işlemi hakkında bilgi içeren bir BitmapData nesnesine ortak işaretçi

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) method

[Bitmap](../)'yi sistem belleğine kilitler.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Kilitlenecek görüntünün bölgesini belirten bir dikdörtgen |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | bitmap'e erişim seviyesini belirtir |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Bu bitmap'in veri biçimi |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Kilitleme işlemi hakkında bilgi içerir |

### Dönüş Değeri

Perform edilen kilitleme işlemi hakkında bilgi içeren bir BitmapData nesnesine ortak işaretçi

## Ayrıca Bakınız

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Sınıf [Rectangle](../../rectangle/)
* Sınıf [Bitmap](../)
* Ad alanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)