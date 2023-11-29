---
title: get_Brush()
second_title: Aspose.Slides for C++ API Reference
description: Gets Brush for the IInkLine IInkBrush Read-only.
type: docs
weight: 1
url: /aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() method


Gets Brush for the IInkLine [IInkBrush](../../iinkbrush/) Read-only.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInkBrush](../../iinkbrush/)
* Class [InkTrace](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)