---
title: get_Brush()
second_title: Aspose.Slides for C++ API Reference
description: Gets Brush for the IInkLine IInkBrush Read-only.
type: docs
weight: 1
url: /aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() method


Gets Brush for the IInkLine [IInkBrush](../../iinkbrush/) Read-only.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
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
* Class [IInkTrace](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)