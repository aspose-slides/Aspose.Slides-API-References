---
title: get_ColumnGapRule()
second_title: Aspose.Slides for C++ API संदर्भ
description: "मैट्रिक्स की कॉलमों के बीच क्षैतिज अंतर की प्रकार; क्षैतिज अंतर की इकाइयाँ ems या points (twips के रूप में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)"
type: docs
weight: 105
url: /hi/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() विधि

एक मैट्रिक्स की कॉलमों के बीच क्षैतिज अंतर की प्रकार; क्षैतिज अंतर की इकाइयाँ ems या points (twips के रूप में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## टिप्पणी

उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## देखें

* Enum [MathSpacingRules](../../mathspacingrules/)
* क्लास [IMathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)