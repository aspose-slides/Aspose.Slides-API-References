---
title: get_ImageType()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar bildtypen för ett zoom-objekt. Läs ZoomImageType. Standardvärde: Preview"
type: docs
weight: 1
url: /sv/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() metod


Hämtar bildtypen för ett zoom-objekt. Läs [ZoomImageType](../../zoomimagetype/). Standardvärde: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## Anmärkningar


Anger om Zoom-objektet använder bildförhandsgranskning eller en omslagsbild. 

Detta exempel visar hur man ändrar Image Type till Preview-värdet. I detta fall ändras den aktuella bilden för ett Zoom-objekt till slide-bild: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Se också

* Enum [ZoomImageType](../../zoomimagetype/)
* Klass [IZoomObject](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)