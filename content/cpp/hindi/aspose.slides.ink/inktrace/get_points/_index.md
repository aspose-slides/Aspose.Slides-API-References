---
title: get_Points()
second_title: Aspose.Slides for C++ API संदर्भ
description: "IInkLine System::Drawing::PointF के लिए बिंदु प्राप्त करता है केवल-पढ़ने योग्य।"
type: docs
weight: 14
url: /hi/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() मेथड

IInkLine के लिए बिंदु प्राप्त करता है [System::Drawing::PointF](../../../system.drawing/pointf/) केवल-पढ़ने योग्य।

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
```

## टिप्पणी

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## देखें भी

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [PointF](../../../system.drawing/pointf/)
* क्लास [InkTrace](../)
* नेमस्पेस [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)