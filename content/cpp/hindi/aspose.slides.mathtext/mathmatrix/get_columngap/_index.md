---
title: get_ColumnGap()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "मैट्रिक्स की कॉलम के बीच क्षैतिज अंतराल का मान; यदि ColumnGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को twips (1/20th of a point) के रूप में व्याख्या किया जाता है। यदि ColumnGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में व्याख्या किया जाता है। अन्य मामलों में इसे अनदेखा किया जाता है। डिफ़ॉल्ट: 0"
type: docs
weight: 131
url: /hi/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() मेथड


मैट्रिक्स की कॉलम के बीच क्षैतिज अंतराल का मान; यदि ColumnGapRule को 3 ("Exactly") पर सेट किया जाता है, तो इकाई को twips (1/20th of a point) के रूप में व्याख्या किया जाता है। यदि ColumnGapRule को 4 ("Multiple") पर सेट किया जाता है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में व्याख्या किया जाता है। अन्य मामलों में यह अनदेखा किया जाता है। डिफ़ॉल्ट: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## टिप्पणी


उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## संबंधित देखें

* क्लास [MathMatrix](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)