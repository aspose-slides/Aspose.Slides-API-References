---
title: GetImage()
second_title: Aspose.Slides için C++ API Referansı
description: "Şekil küçük resmi döndürür. ShapeThumbnailBounds::Shape şekil küçük resmi sınır türü varsayılan olarak kullanılır."
type: docs
weight: 547
url: /tr/aspose.slides/ishape/getimage/
---
## IShape::GetImage() metodu

Şekil küçük resmi döndürür. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) şekil küçük resmi sınırları türü varsayılan olarak kullanılır.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```

### Dönüş Değeri

[Shape](../../shape/) küçük resim.

## IShape::GetImage(ShapeThumbnailBounds, float, float) metodu

Şekil küçük resmi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) küçük resim sınırları türü. |
| scaleX | **float** | X ölçeği |
| scaleY | **float** | Y ölçeği |

### Dönüş Değeri

[Shape](../../shape/) küçük resim veya [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) kullanıldığında ve bir şeklin görünür öğeleri olmadığında null.

## Bakınız

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IImage](../../iimage/)
* Sınıf [IShape](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)