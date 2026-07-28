---
title: get_ImageType()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Pobiera typ obrazu obiektu Zoom. Zobacz ZoomImageType. Domyślna wartość: Preview"
type: docs
weight: 1
url: /pl/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() method


Pobiera typ obrazu obiektu Zoom. Zobacz [ZoomImageType](../../zoomimagetype/). Domyślna wartość: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## Uwagi


Określa, czy obiekt Zoom używa podglądu slajdu lub obrazu okładki. 

Ten przykład pokazuje zmianę wartości Image Type na Preview. W tym przypadku bieżący obraz obiektu Zoom zostaje zmieniony na obraz slajdu: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Zobacz także

* Wyliczenie [ZoomImageType](../../zoomimagetype/)
* Klasa [IZoomObject](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)