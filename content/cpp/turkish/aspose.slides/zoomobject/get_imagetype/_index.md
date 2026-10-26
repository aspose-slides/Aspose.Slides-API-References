---
title: get_ImageType()
second_title: Aspose.Slides için C++ API Referansı
description: "Bir yakınlaştırma nesnesinin görüntü türünü alır. ZoomImageType okuyun. Varsayılan değer: Preview"
type: docs
weight: 1
url: /tr/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() metodu


Zoom nesnesinin görüntü türünü alır. [ZoomImageType](../../zoomimagetype/) okuyun. Varsayılan değer: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## Açıklamalar


Zoom nesnesinin slayt önizlemesini mi yoksa kapak resmini mi kullandığını belirtir.

Sonraki örnek, Image Type'ı Preview değerine değiştirmeyi gösterir. Bu durumda bir Zoom nesnesinin geçerli resmi slayt resmi olarak değişir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Ayrıca Bakınız

* Enum [ZoomImageType](../../zoomimagetype/)
* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)