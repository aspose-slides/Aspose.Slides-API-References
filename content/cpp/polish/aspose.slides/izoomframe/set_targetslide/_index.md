---
title: set_TargetSlide()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Ustawia obiekt slajdu, do którego odwołuje się obiekt Slide Zoom. Zapisz ISlide.
type: docs
weight: 14
url: /pl/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) metoda

Ustawia obiekt slajdu, do którego odwołuje się obiekt [Slide](../../slide/) Zoom. Zapisz [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
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
* Klasa [IZoomFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)