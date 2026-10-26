---
title: set_ImageType()
second_title: Aspose.Slides dla C++ API Reference
description: "Ustawia typ obrazu obiektu Zoom. Zapisz ZoomImageType. Domyślna wartość: Preview"
type: docs
weight: 14
url: /pl/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) metoda


Ustawia typ obrazu obiektu Zoom. Napisz [ZoomImageType](../../zoomimagetype/). Domyślna wartość: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## Uwagi


Określa, czy obiekt Zoom używa podglądu slajdu, czy obrazu okładki. 

Następny przykład demonstruje zmianę typu obrazu na wartość Preview. W tym przypadku bieżący obraz obiektu Zoom zmienia się na obraz slajdu: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Zobacz także

* Wyliczenie [ZoomImageType](../../zoomimagetype/)
* Klasa [ZoomObject](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)