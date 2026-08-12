---
title: get_RowGap()
second_title: Aspose.Slides for C++ API संदर्भ
description: "मैट्रिक्स की पंक्तियों के बीच लंबवत अंतराल का मान; यदि RowGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को ट्विप्स (1/20th of a point) के रूप में व्याख्यायित किया जाता है यदि RowGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को आधी-लाइन के रूप में व्याख्यायित किया जाता है। डिफ़ॉल्ट: 0"
type: docs
weight: 183
url: /hi/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() मेथड


मैट्रिक्स की पंक्तियों के बीच लंबवत अंतराल का मान; यदि RowGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को ट्विप्स (1/20th of a point) के रूप में व्याख्यायित किया जाता है। यदि RowGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को आधी-लाइन के रूप में व्याख्यायित किया जाता है। डिफ़ॉल्ट: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## संबंधित देखें

* क्लास [IMathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)