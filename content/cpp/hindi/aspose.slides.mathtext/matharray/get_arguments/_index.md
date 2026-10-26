---
title: get_Arguments()
second_title: Aspose.Slides for C++ API संदर्भ
description: एरे के आइटम का सेट
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() विधि

एरे के आइटम का सेट

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## टिप्पणी

उदाहरण:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElementCollection](../../imathelementcollection/)
* क्लास [MathArray](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)