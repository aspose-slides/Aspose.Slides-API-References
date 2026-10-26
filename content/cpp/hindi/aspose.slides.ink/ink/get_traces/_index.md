---
title: get_Traces()
second_title: Aspose.Slides for C++ API संदर्भ
description: IInk तत्व IInkTrace में सम्मिलित सभी ट्रेस प्राप्त करता है। केवल- पढ़ने योग्य।
type: docs
weight: 1
url: /hi/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() विधि


सभी ट्रेस प्राप्त करता है जो [IInk](../../iink/) तत्व [IInkTrace](../../iinktrace/) में सम्मिलित हैं। केवल-पढ़ने योग्य।

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## टिप्पणी


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IInkTrace](../../iinktrace/)
* क्लास [Ink](../)
* नामस्थान [Aspose::Slides::Ink](../../)
* लाइब्रेरी [Aspose.Slides](../../../)