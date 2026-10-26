---
title: get_RowGap()
second_title: "Aspose.Slides C++ के लिए API संदर्भ"
description: "मैट्रिक्स की पंक्तियों के बीच लंबवत अंतराल का मान; यदि RowGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को टविप्स (एक बिंदु का 1/20) के रूप में व्याख्यायित किया जाता है। यदि RowGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को अर्ध-रेखाओं के रूप में व्याख्यायित किया जाता है। डिफ़ॉल्ट: 0"
type: docs
weight: 183
url: /hi/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() विधि

एक मैट्रिक्स की पंक्तियों के बीच लंबवत अंतराल का मान; यदि RowGapRule को 3 ("Exactly") पर सेट किया गया है, तो इकाई को टविप्स (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है। यदि RowGapRule को 4 ("Multiple") पर सेट किया गया है, तो इकाई को अर्द्ध-रेखाओं के रूप में व्याख्यायित किया जाता है। डिफ़ॉल्ट: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## टिप्पणियां

उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## देखें

* कक्षा [MathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)