---
title: set_Size()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक लाइन के लिए ब्रश का आकार पॉइंट्स में सेट करता है।
type: docs
weight: 40
url: /hi/aspose.slides.ink/inkbrush/set_size/
---
## InkBrush::set_Size(System::Drawing::SizeF) विधि


लाइन के लिए ब्रश का आकार पॉइंट्स में सेट करता है।

```cpp
void Aspose::Slides::Ink::InkBrush::set_Size(System::Drawing::SizeF value) override
```

## टिप्पणी


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## संबंधित देखें

* क्लास [SizeF](../../../system.drawing/sizef/)
* क्लास [InkBrush](../)
* नामस्थान [Aspose::Slides::Ink](../../)
* लाइब्रेरी [Aspose.Slides](../../../)