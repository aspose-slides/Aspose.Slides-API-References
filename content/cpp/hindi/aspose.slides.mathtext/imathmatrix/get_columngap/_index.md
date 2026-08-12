---
title: get_ColumnGap()
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक मैट्रिक्स के स्तंभों के बीच क्षैतिज अंतराल का मान; यदि ColumnGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को टविप्स (1/20 बिंदु) के रूप में व्याख्यायित किया जाता है यदि ColumnGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में व्याख्यायित किया जाता है। अन्य मामलों में इसे नजरअंदाज किया जाता है। डिफ़ॉल्ट: 0"
type: docs
weight: 131
url: /hi/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() विधि

एक मैट्रिक्स की स्तंभों के बीच क्षैतिज अंतराल का मान; यदि ColumnGapRule को 3 ("Exactly") पर सेट किया जाता है, तो इकाई को टविप्स (एक बिंदु का 1/20 हिस्सा) के रूप में व्याख्यायित किया जाता है। यदि ColumnGapRule को 4 ("Multiple") पर सेट किया जाता है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में व्याख्यायित किया जाता है। अन्य मामलों में इसे नजरअंदाज किया जाता है। डिफ़ॉल्ट: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## देखें भी

* क्लास [IMathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)