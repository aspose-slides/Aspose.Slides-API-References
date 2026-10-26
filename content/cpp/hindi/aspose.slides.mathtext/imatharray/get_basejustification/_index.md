---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API संदर्भ
description: "एरे के आसपास के पाठ के सापेक्ष संरेखण निर्दिष्ट करता है। एरे के बाहर का पाठ एरे ऑब्जेक्ट के नीचे, ऊपर, या केंद्र में संरेखित किया जा सकता है। डिफ़ॉल्ट मान: Center"
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() विधि


एरे के आसपास के पाठ के सापेक्ष संरेखण निर्दिष्ट करता है। एरे के बाहर का पाठ एरे ऑब्जेक्ट के नीचे, ऊपर, या केंद्र में संरेखित किया जा सकता है। डिफ़ॉल्ट मान: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## टिप्पणी


उदाहरण: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## संबंधित देखें

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)