---
title: get_Points()
second_title: Aspose.Slides for C++ API संदर्भ
description: "IInkLine System::Drawing::PointF के लिए बिंदु प्राप्त करता है। केवल पढ़ने योग्य।"
type: docs
weight: 14
url: /hi/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() विधि

IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) के लिए बिंदु प्राप्त करता है। केवल पढ़ने योग्य।

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [PointF](../../../system.drawing/pointf/)
* क्लास [IInkTrace](../)
* नामस्थान [Aspose::Slides::Ink](../../)
* लाइब्रेरी [Aspose.Slides](../../../)