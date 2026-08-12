---
title: set_Color()
second_title: Aspose.Slides for C++ API संदर्भ
description: लाइन के लिए ब्रश रंग सेट करता है।
type: docs
weight: 14
url: /hi/aspose.slides.ink/iinkbrush/set_color/
---
## IInkBrush::set_Color(System::Drawing::Color) विधि


लाइन के लिए ब्रश का रंग सेट करता है।

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Color(System::Drawing::Color value)=0
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

## देखें

* क्लास [Color](../../../system.drawing/color/)
* क्लास [IInkBrush](../)
* नामस्थान [Aspose::Slides::Ink](../../)
* लाइब्रेरी [Aspose.Slides](../../../)