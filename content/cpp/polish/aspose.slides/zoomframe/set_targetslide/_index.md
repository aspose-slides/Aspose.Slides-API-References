---
title: set_TargetSlide()
second_title: Aspose.Slides dla C++ – referencja API
description: Ustawia obiekt slajdu, do którego odnosi się obiekt Slide Zoom. Zapisz ISlide.
type: docs
weight: 14
url: /pl/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) metoda

Ustawia obiekt slajdu, do którego odwołuje się obiekt Zoom [Slide](../../slide/). Zapisz [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## Uwagi

Następny przykład demonstruje zmianę docelowego slajdu i tworzy nowy obraz dla obiektu Zoom [Slide](../../slide/):
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlide](../../islide/)
* Klasa [ZoomFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)