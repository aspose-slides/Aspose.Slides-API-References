---
title: get_Points()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar punkter för IInkLine System::Drawing::PointF skrivskyddad."
type: docs
weight: 14
url: /sv/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() metod


Hämtar punkter för IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) skrivskyddad.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
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

* Typdef [ArrayPtr](../../../system/arrayptr/)
* Klass [PointF](../../../system.drawing/pointf/)
* Klass [InkTrace](../)
* Namnrymd [Aspose::Slides::Ink](../../)
* Bibliotek [Aspose.Slides](../../../)