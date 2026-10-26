---
title: get_RowGapRule()
second_title: Aspose.Slides for C++ API संदर्भ
description: "मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर अंतर का प्रकार; ऊर्ध्वाधर अंतर इकाइयाँ लाइन्स या पॉइंट्स (ट्विप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)"
type: docs
weight: 157
url: /hi/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() मेथड


मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर अंतर का प्रकार; ऊर्ध्वाधर अंतर इकाइयाँ लाइनें या पॉइंट (ट्विप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## संबंधित देखें

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)