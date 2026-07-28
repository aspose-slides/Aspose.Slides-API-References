---
title: get_Points()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Pobiera punkty dla IInkLine System::Drawing::PointF Tylko do odczytu."
type: docs
weight: 14
url: /pl/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() metoda

Pobiera punkty dla IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Tylko do odczytu.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
```

## Uwagi

Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* klasa [PointF](../../../system.drawing/pointf/)
* klasa [InkTrace](../)
* Przestrzeń nazw [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)