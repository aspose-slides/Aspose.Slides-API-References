---
title: get_Traces()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: IInk तत्व IInkTrace में सम्मिलित सभी ट्रेस प्राप्त करता है। केवल पढ़ने योग्य।
type: docs
weight: 1
url: /hi/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() विधि

सभी ट्रेस को प्राप्त करता है जो [IInk](../) तत्व [IInkTrace](../../iinktrace/) में सम्मिलित हैं। केवल पढ़ने योग्य।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## टिप्पणी

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IInkTrace](../../iinktrace/)
* क्लास [IInk](../)
* नेमस्पेस [Aspose::Slides::Ink](../../)
* लाइब्रेरी [Aspose.Slides](../../../)