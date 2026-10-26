---
title: set_ImageType()
second_title: Aspose.Slides için C++ API Referansı
description: "Zoom nesnesinin resim türünü ayarlar. ZoomImageType yazın. Varsayılan değer: Preview"
type: docs
weight: 14
url: /tr/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) metodu

Zoom nesnesinin resim türünü ayarlar. [ZoomImageType](../../zoomimagetype/) yazın. Varsayılan değer: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## Açıklamalar

Zoom nesnesinin slayt önizlemesi mi yoksa kapak resmi mi kullandığını belirtir.

Sonraki örnek, Image Type değerinin Preview olarak değiştirilmesini gösterir. Bu durumda bir Zoom nesnesinin mevcut resmi slayt resmine değişir:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## İlgili

* Enum [ZoomImageType](../../zoomimagetype/)
* Sınıf [ZoomObject](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)