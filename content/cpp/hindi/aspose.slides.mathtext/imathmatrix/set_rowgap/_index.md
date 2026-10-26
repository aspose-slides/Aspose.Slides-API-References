---
title: set_RowGap()
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक मैट्रिक्स की पंक्तियों के बीच लंबवत अंतर का मान; यदि RowGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को टविप्स (एक बिंदु का 1/20 हिस्सा) के रूप में व्याख्यायित किया जाता है। यदि RowGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को आधी-लाइन के रूप में व्याख्यायित किया जाता है। डिफ़ॉल्ट: 0"
type: docs
weight: 196
url: /hi/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) विधि

एक मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का मान; यदि RowGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को टविप्स (एक पॉइंट का 1/20 हिस्सा) के रूप में व्याख्यायित किया जाता है। यदि RowGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को आधी-लाइन के रूप में व्याख्यायित किया जाता है। डिफ़ॉल्ट: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
```

## टिप्पणी

उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## देखें

* क्लास [IMathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)