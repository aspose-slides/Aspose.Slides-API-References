---
title: GetImage()
second_title: Aspose.Slides for C++ API Referansı
description: "Şekil mini resmini döndürür. ShapeThumbnailBounds::Shape şekil mini resim sınırları türü varsayılan olarak kullanılır."
type: docs
weight: 651
url: /tr/aspose.slides/shape/getimage/
---
## Shape::GetImage() yöntemi


Şekil mini resmi döndürür. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) shape thumbnail bounds type varsayılan olarak kullanılır.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```


### Dönüş Değeri

[Shape](../) mini resim.

## Shape::GetImage(ShapeThumbnailBounds, float, float) yöntemi


Şekil mini resmi döndürür.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) mini resim sınırları türü. |
| scaleX | **float** | X ölçeği |
| scaleY | **float** | Y ölçeği |

### Dönüş Değeri

[Shape](../) mini resim veya null, [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) kullanıldığında ve bir şeklin görünür öğeleri olmadığında.

## Ayrıca Bakınız

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)