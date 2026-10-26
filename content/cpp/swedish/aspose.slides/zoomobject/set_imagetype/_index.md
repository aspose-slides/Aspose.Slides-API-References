---
title: set_ImageType()
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in bildtypen för ett zoom-objekt. Skriv ZoomImageType. Standardvärde: Preview"
type: docs
weight: 14
url: /sv/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) metod

Ställer in bildtypen för ett zoom-objekt. Skriv [ZoomImageType](../../zoomimagetype/). Standardvärde: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## Anmärkningar

Anger om Zoom-objektet använder bildförhandsgranskning eller en omslagsbild.

Nästa exempel visar hur man ändrar Image Type till Preview-värdet. I detta fall ändras den aktuella bilden för ett Zoom-objekt till slide-bild:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Se också

* Enum [ZoomImageType](../../zoomimagetype/)
* Klass [ZoomObject](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)