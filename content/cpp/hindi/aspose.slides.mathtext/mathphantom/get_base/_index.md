---
title: get_Base()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Base आर्ग्युमेंट
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/mathphantom/get_base/
---
## MathPhantom::get_Base() विधि

Base आर्ग्युमेंट

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathPhantom::get_Base() override
```

## टिप्पणी

उदाहरण:
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathPhantom](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)