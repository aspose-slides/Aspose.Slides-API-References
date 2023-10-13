---
title: get_Size()
second_title: Aspose.Slides for C++ API Reference
description: Gets the brush size for a line in points.
type: docs
weight: 27
url: /aspose.slides.ink/inkbrush/get_size/
---
## InkBrush::get_Size() method


Gets the brush size for a line in points.

```cpp
System::Drawing::SizeF Aspose::Slides::Ink::InkBrush::get_Size() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## See Also

* Class [SizeF](../../../system.drawing/sizef/)
* Class [InkBrush](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)