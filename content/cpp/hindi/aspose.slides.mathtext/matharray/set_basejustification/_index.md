---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API संदर्भ
description: "एरे की संरेखण को आसपास के पाठ के सापेक्ष निर्दिष्ट करता है। एरे के बाहर का पाठ एरे वस्तु के नीचे, ऊपर, या केंद्र के साथ संरेखित किया जा सकता है। डिफ़ॉल्ट मान: Center"
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) विधि

एरे की संरेखण को आस-पास के पाठ के सापेक्ष निर्दिष्ट करता है। एरे के बाहर का पाठ एरे वस्तु के नीचे, ऊपर, या केंद्र के साथ संरेखित किया जा सकता है। डिफ़ॉल्ट मान: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## संबंधित देखें

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* क्लास [MathArray](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)