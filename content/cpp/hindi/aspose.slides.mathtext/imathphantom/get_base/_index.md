---
title: get_Base()
second_title: Aspose.Slides for C++ API संदर्भ
description: Base तर्क
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathphantom/get_base/
---
## IMathPhantom::get_Base() विधि


Base आर्ग्यूमेंट

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathPhantom::get_Base()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathPhantom](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)