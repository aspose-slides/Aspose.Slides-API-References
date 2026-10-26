---
title: set_ColumnGap()
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक मैट्रिक्स की कॉलम के बीच क्षैतिज अंतराल का मान; यदि ColumnGapRule को 3 (\"Exactly\") पर सेट किया गया है, तो इकाई को टविप्स (1/20वां पॉइंट) के रूप में व्याख्यायित किया जाता है। यदि ColumnGapRule को 4 (\"Multiple\") पर सेट किया गया है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में व्याख्यायित किया जाता है। अन्य मामलों में इसे नज़रअंदाज़ किया जाता है। डिफ़ॉल्ट: 0"
type: docs
weight: 144
url: /hi/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) विधि


एक मैट्रिक्स की कॉलम के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule को 3 (\"Exactly\") पर सेट किया गया है, तो इकाई को टविप्स (1/20th of a point) के रूप में व्याख्यायित किया जाता है। यदि ColumnGapRule को 4 (\"Multiple\") पर सेट किया गया है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में व्याख्यायित किया जाता है। अन्य मामलों में अनदेखा किया जाता है। डिफ़ॉल्ट: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
```

## टिप्पणी


उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## देखें

* क्लास [MathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)