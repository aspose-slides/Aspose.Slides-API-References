---
title: get_Points()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Pobiera punkty dla IInkLine System::Drawing::PointF tylko do odczytu."
type: docs
weight: 14
url: /pl/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() metoda


Pobiera punkty dla IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Tylko do odczytu.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
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
* Klasa [PointF](../../../system.drawing/pointf/)
* Klasa [IInkTrace](../)
* Przestrzeń nazw [Aspose::Slides::Ink](../../)
* Biblioteka [Aspose.Slides](../../../)