---
title: get_Points()
second_title: Aspose.Slides for C++ API Reference
description: "Gets points for the IInkLine System::Drawing::PointF Read-only."
type: docs
weight: 14
url: /aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() method


Gets points for the IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Read-only.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [InkTrace](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)