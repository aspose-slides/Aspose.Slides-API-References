---
title: set_ImageType()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Ustawia typ obrazu obiektu zoom. Zapisz ZoomImageType. Wartość domyślna: Preview"
type: docs
weight: 14
url: /pl/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) method


Ustawia typ obrazu obiektu zoom. Zapisz [ZoomImageType](../../zoomimagetype/). Wartość domyślna: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## Uwagi


Określa, czy obiekt Zoom używa podglądu slajdu, czy obrazu okładki. 

Ten przykład demonstruje zmianę typu obrazu na wartość Preview. W tym przypadku bieżący obraz obiektu Zoom zmienia się na obraz slajdu: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Zobacz także

* Enum [ZoomImageType](../../zoomimagetype/)
* Class [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)