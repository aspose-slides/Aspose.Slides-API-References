---
title: get_Color()
second_title: Aspose.Slides for C++ API संदर्भ
description: लाइन के लिए ब्रश रंग प्राप्त करता है।
type: docs
weight: 1
url: /hi/aspose.slides.ink/inkbrush/get_color/
---
## InkBrush::get_Color() विधि

लाइन के लिए ब्रश रंग प्राप्त करता है।

```cpp
System::Drawing::Color Aspose::Slides::Ink::InkBrush::get_Color() override
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
* क्लास [InkBrush](../)
* नेमस्पेस [Aspose::Slides::Ink](../../)
* लाइब्रेरी [Aspose.Slides](../../../)