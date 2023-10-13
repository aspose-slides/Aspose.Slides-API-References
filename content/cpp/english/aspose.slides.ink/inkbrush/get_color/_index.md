---
title: get_Color()
second_title: Aspose.Slides for C++ API Reference
description: Gets the brush color for a line.
type: docs
weight: 1
url: /aspose.slides.ink/inkbrush/get_color/
---
## InkBrush::get_Color() method


Gets the brush color for a line.

```cpp
System::Drawing::Color Aspose::Slides::Ink::InkBrush::get_Color() override
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
* Class [InkBrush](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)