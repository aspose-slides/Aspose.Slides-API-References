---
title: get_Arguments()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ऐरे के आइटमों का सेट
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() मेथड

ऐरे के आइटमों का सेट

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## टिप्पणी

उदाहरण:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElementCollection](../../imathelementcollection/)
* क्लास [IMathArray](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)