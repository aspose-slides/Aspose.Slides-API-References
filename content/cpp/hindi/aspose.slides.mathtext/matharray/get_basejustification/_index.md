---
title: get_BaseJustification()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "ऐरे की संरेखण को आसपास के पाठ के सापेक्ष निर्दिष्ट करता है। ऐरे के बाहर का पाठ ऐरे वस्तु के नीचे, ऊपर, या मध्य में संरेखित किया जा सकता है। डिफ़ॉल्ट मान: Center"
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() विधि

ऐरे की प्रविन्यास को आसपास के टेक्स्ट के सापेक्ष निर्दिष्ट करता है। ऐरे के बाहर का टेक्स्ट ऐरे वस्तु के नीचे, ऊपर, या बीच में संरेखित किया जा सकता है। डिफ़ॉल्ट मान: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## देखें

* एनम [MathVerticalAlignment](../../mathverticalalignment/)
* क्लास [MathArray](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)