---
title: get_ImageType()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Pobiera typ obrazu obiektu Zoom. Przeczytaj ZoomImageType. Domyślna wartość: Preview"
type: docs
weight: 1
url: /pl/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() metoda

Pobiera typ obrazu obiektu Zoom. Przeczytaj [ZoomImageType](../../zoomimagetype/). Domyślna wartość: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## Uwagi

Określa, czy obiekt Zoom używa podglądu slajdu lub obrazu okładki. 

Poniższy przykład demonstruje zmianę Image Type na wartość Preview. W tym przypadku bieżący obraz obiektu Zoom zmienia się na obraz slajdu: 
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