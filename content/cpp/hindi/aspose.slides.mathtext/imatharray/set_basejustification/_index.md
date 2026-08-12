---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API संदर्भ
description: "ऐरे को आसपास के टेक्स्ट के सापेक्ष संरेखित करने को निर्दिष्ट करता है। ऐरे के बाहर का टेक्स्ट ऐरे ऑब्जेक्ट के नीचे, ऊपर या मध्य में संरेखित किया जा सकता है। डिफ़ॉल्ट मान: Center"
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) विधि

ऐरे की संरेखण को आसपास के टेक्स्ट के सापेक्ष निर्दिष्ट करता है। ऐरे के बाहर का टेक्स्ट ऐरे ऑब्जेक्ट के नीचे, ऊपर या मध्य में संरेखित किया जा सकता है। डिफ़ॉल्ट मान: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## टिप्पणी

उदाहरण:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## देखें

* एनम [MathVerticalAlignment](../../mathverticalalignment/)
* क्लास [IMathArray](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)