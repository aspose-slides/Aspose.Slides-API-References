---
title: set_Size()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: लाइन के लिए ब्रश का आकार पॉइंट्स में सेट करता है।
type: docs
weight: 40
url: /hi/aspose.slides.ink/iinkbrush/set_size/
---
## IInkBrush::set_Size(System::Drawing::SizeF) मेथड

सेट ब्रश का आकार एक लाइन के लिए पॉइंट्स में।

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Size(System::Drawing::SizeF value)=0
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

## संबंधित देखें

* क्लास [SizeF](../../../system.drawing/sizef/)
* क्लास [IInkBrush](../)
* नेमस्पेस [Aspose::Slides::Ink](../../)
* लाइब्रेरी [Aspose.Slides](../../../)