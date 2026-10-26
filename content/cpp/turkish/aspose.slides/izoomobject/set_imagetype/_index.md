---
title: set_ImageType()
second_title: Aspose.Slides için C++ API Referansı
description: "Zoom nesnesinin görüntü tipini ayarlar. ZoomImageType yazın. Varsayılan değer: Preview"
type: docs
weight: 14
url: /tr/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) metot

Bir yakınlaştırma nesnesinin görüntü tipini ayarlar. [ZoomImageType](../../zoomimagetype/) yazın. Varsayılan değer: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## Açıklamalar

Zoom nesnesinin slayt önizlemesini mi yoksa bir kapak görüntüsünü mü kullandığını belirtir.

Bu örnek, Image Type'ı Preview değerine değiştirmeyi gösterir. Bu durumda bir Zoom nesnesinin mevcut görüntüsü slayt görüntüsüne değişir:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Ayrıca

* Enum [ZoomImageType](../../zoomimagetype/)
* Class [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)