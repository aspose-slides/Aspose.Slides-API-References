---
title: Clone()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli nesnenin bir kopyasını oluşturur.
type: docs
weight: 183
url: /tr/system.drawing/bitmap/clone/
---
## Bitmap::Clone() metot

Geçerli nesnenin bir kopyasını oluşturur.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### Dönüş Değeri

Geçerli nesnenin bir kopyası.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) metot

[Bitmap](../) nesnesini oluşturur; bu nesne, geçerli nesne tarafından temsil edilen bitmap görüntüsünün bir bölgesinin kopyasını temsil eder.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Kopyalanacak bölgeyi belirten dikdörtgen |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Yeni [Bitmap](../) için piksel formatı |

### Dönüş Değeri

Oluşturulan [Bitmap](../) nesnesi

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) metot

[Bitmap](../) nesnesini oluşturur; bu nesne, geçerli nesne tarafından temsil edilen bitmap görüntüsünün bir bölgesinin kopyasını temsil eder.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Kopyalanacak bölgeyi belirten dikdörtgen |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Yeni [Bitmap](../) için piksel formatı |

### Dönüş Değeri

Oluşturulan [Bitmap](../) nesnesi

## İlgili

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Image](../../image/)
* Sınıf [Bitmap](../)
* Sınıf [Rectangle](../../rectangle/)
* Sınıf [RectangleF](../../rectanglef/)
* Ad alanı [System::Drawing](../../)
* Library [Aspose.Slides](../../../)