---
title: get_Points()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar punkter för IInkLine System::Drawing::PointF skrivskyddad."
type: docs
weight: 14
url: /sv/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() metod


Hämtar punkter för IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) skrivskyddad.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [PointF](../../../system.drawing/pointf/)
* Klass [IInkTrace](../)
* Namnrymd [Aspose::Slides::Ink](../../)
* Bibliotek [Aspose.Slides](../../../)