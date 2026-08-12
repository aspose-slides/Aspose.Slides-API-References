---
title: get_Base()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Base तर्क
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() विधि

Base तर्क

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathRadical](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)