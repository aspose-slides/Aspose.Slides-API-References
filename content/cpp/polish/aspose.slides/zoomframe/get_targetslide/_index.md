---
title: get_TargetSlide()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Pobiera obiekt slajdu, do którego odwołuje się obiekt Slide Zoom. Przeczytaj ISlide.
type: docs
weight: 1
url: /pl/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() metoda


Pobiera obiekt slajdu, do którego odwołuje się obiekt [Slide](../../slide/) Zoom. Przeczytaj [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Uwagi


Poniższy przykład demonstruje zmianę docelowego slajdu i tworzy nowy obraz dla obiektu [Slide](../../slide/) Zoom: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlide](../../islide/)
* Klasa [ZoomFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)