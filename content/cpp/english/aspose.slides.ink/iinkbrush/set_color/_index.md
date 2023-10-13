---
title: set_Color()
second_title: Aspose.Slides for C++ API Reference
description: Sets the brush color for a line.
type: docs
weight: 14
url: /aspose.slides.ink/iinkbrush/set_color/
---
## IInkBrush::set_Color(System::Drawing::Color) method


Sets the brush color for a line.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Color(System::Drawing::Color value)=0
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## See Also

* Class [Color](../../../system.drawing/color/)
* Class [IInkBrush](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)