---
title: set_RowGap()
second_title: Aspose.Slides for C++ API संदर्भ
description: "मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का मान; यदि RowGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को ट्विप्स (बिंदु का 1/20 भाग) के रूप में व्याख्यायित किया जाता है यदि RowGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को आधी-लाइन के रूप में व्याख्यायित किया जाता है। डिफ़ॉल्ट: 0"
type: docs
weight: 196
url: /hi/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) मेथड

एक मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का मान; यदि RowGapRule को 3 (\"Exactly\") पर सेट किया गया है, तो इकाई को ट्विप्स (बिंदु का 1/20 भाग) के रूप में व्याख्यायित किया जाता है यदि RowGapRule को 4 (\"Multiple\") पर सेट किया गया है, तो इकाई को आधी-लाइन के रूप में व्याख्यायित किया जाता है। डिफ़ॉल्ट: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## टिप्पणी

उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## देखें

* क्लास [MathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)