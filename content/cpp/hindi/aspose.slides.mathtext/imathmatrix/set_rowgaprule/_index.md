---
title: set_RowGapRule()
second_title: Aspose.Slides for C++ API संदर्भ
description: "मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर अंतर का प्रकार; ऊर्ध्वाधर अंतर इकाइयाँ लाइनें या बिंदु (twips में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)"
type: docs
weight: 170
url: /hi/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) मेथड


मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर अंतर का प्रकार; ऊर्ध्वाधर अंतर इकाइयाँ लाइनें या बिंदु (twips में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
```

## टिप्पणी


उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## संबंधित देखें

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)