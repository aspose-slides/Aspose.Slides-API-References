---
title: set_ImageType()
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in bildtypen för ett zoom-objekt. Skriv ZoomImageType. Standardvärde: Preview"
type: docs
weight: 14
url: /sv/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) metod

Ställer in bildtypen för ett Zoom-objekt. Skriv [ZoomImageType](../../zoomimagetype/). Standardvärde: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## Anmärkningar

Anger om Zoom-objektet använder bildförhandsvisning eller en omslagsbild. 

Detta exempel demonstrerar hur man ändrar Image Type till värdet Preview. I detta fall ändras den aktuella bilden för ett Zoom-objekt till bild för bildspel:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Se även

* Enum [ZoomImageType](../../zoomimagetype/)
* Klass [IZoomObject](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)