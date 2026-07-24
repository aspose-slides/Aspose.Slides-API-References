---
title: get_ImageType()
second_title: Aspose.Slides for C++ API Referansı
description: "Bir zoom nesnesinin görüntü türünü alır. ZoomImageType oku. Varsayılan değer: Preview"
type: docs
weight: 1
url: /tr/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() method

Bir zoom nesnesinin görüntü türünü alır. Oku [ZoomImageType](../../zoomimagetype/). Varsayılan değer: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## Açıklamalar

Zoom nesnesinin slayt önizlemesi mi yoksa bir kapak resmi mi kullandığını belirtir.

Bu örnek, Image Type'ı Preview değerine değiştirmeyi gösterir. Bu durumda bir Zoom nesnesinin geçerli resmi slayt resmine değişir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Ayrıca Bakınız

* Enum [ZoomImageType](../../zoomimagetype/)
* Class [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)