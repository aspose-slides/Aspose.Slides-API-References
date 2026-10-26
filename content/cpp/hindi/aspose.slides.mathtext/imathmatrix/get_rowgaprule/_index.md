---
title: get_RowGapRule()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर अंतराल का प्रकार; ऊर्ध्वाधर अंतराल इकाइयाँ रेखाएं या बिंदु (twips के रूप में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)"
type: docs
weight: 157
url: /hi/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() विधि

मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर अंतराल का प्रकार; ऊर्ध्वाधर अंतराल इकाइयाँ रेखाएँ या बिंदु (twips के रूप में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## देखें

* Enum [MathSpacingRules](../../mathspacingrules/)
* क्लास [IMathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)