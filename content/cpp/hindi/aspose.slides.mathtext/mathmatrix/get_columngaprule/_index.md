---
title: get_ColumnGapRule()
second_title: Aspose.Slides for C++ API संदर्भ
description: "मैट्रिक्स की कॉलमों के बीच क्षैतिज अंतराल का प्रकार; क्षैतिज अंतराल इकाइयाँ ems या पॉइंट्स (twips में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)"
type: docs
weight: 105
url: /hi/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() मेथड

The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## टिप्पणी

उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## देखें

* एनम [MathSpacingRules](../../mathspacingrules/)
* क्लास [MathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)