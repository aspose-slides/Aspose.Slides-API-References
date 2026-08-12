---
title: set_ColumnGapRule()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "मैट्रिक्स की कॉलम के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या points (twips के रूप में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)"
type: docs
weight: 118
url: /hi/aspose.slides.mathtext/mathmatrix/set_columngaprule/
---
## MathMatrix::set_ColumnGapRule(MathSpacingRules) मेथड

एक मैट्रिक्स की कॉलम के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट्स (twips के रूप में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGapRule(MathSpacingRules value) override
```

## टिप्पणी

उदाहरण:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## संबंधित देखें

* Enum [MathSpacingRules](../../mathspacingrules/)
* क्लास [MathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)