---
title: get_Brush()
second_title: Aspose.Slides for C++ API संदर्भ
description: IInkLine IInkBrush के लिए Brush प्राप्त करता है केवल-पढ़ने योग्य।
type: docs
weight: 1
url: /hi/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() विधि

IInkLine [IInkBrush](../../iinkbrush/) के लिए Brush प्राप्त करता है केवल-पढ़ने योग्य।

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
```

## टिप्पणी

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IInkBrush](../../iinkbrush/)
* क्लास [InkTrace](../)
* नेमस्पेस [Aspose::Slides::Ink](../../)
* लाइब्रेरी [Aspose.Slides](../../../)