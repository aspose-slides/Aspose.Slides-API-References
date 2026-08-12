---
title: get_Size()
second_title: Aspose.Slides for C++ API संदर्भ
description: लाइन के लिए ब्रश आकार पॉइंट्स में प्राप्त करता है।
type: docs
weight: 27
url: /hi/aspose.slides.ink/iinkbrush/get_size/
---
## IInkBrush::get_Size() विधि


लाइन के लिए ब्रश आकार पॉइंट्स में प्राप्त करता है।

```cpp
virtual System::Drawing::SizeF Aspose::Slides::Ink::IInkBrush::get_Size()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## देखें

* क्लास [SizeF](../../../system.drawing/sizef/)
* क्लास [IInkBrush](../)
* नामस्थान [Aspose::Slides::Ink](../../)
* लाइब्रेरी [Aspose.Slides](../../../)