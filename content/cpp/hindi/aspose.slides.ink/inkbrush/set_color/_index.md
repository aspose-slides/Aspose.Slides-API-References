---
title: set_Color()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: रेखा के लिए ब्रश का रंग सेट करता है।
type: docs
weight: 14
url: /hi/aspose.slides.ink/inkbrush/set_color/
---
## InkBrush::set_Color(System::Drawing::Color) विधि

एक रेखा के लिए ब्रश का रंग सेट करता है।

```cpp
void Aspose::Slides::Ink::InkBrush::set_Color(System::Drawing::Color value) override
```

## टिप्पणियाँ

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## देखें भी

* क्लास [Color](../../../system.drawing/color/)
* क्लास [InkBrush](../)
* नामस्थान [Aspose::Slides::Ink](../../)
* लाइब्रेरी [Aspose.Slides](../../../)