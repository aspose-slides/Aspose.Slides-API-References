---
title: set_ColumnGap()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "एक मैट्रिक्स की कॉलमों के बीच क्षैतिज अंतराल का मान; यदि ColumnGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को टविप्स (1/20वाँ पॉइंट) के रूप में व्याख्यायित किया जाता है। यदि ColumnGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को 0.5 इम इंक्रीमेंट की संख्या के रूप में व्याख्यायित किया जाता है। अन्य मामलों में इसे अनदेखा किया जाता है। डिफ़ॉल्ट: 0"
type: docs
weight: 144
url: /hi/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) विधि

मैट्रिक्स की कॉलम के बीच क्षैतिज अंतराल का मान; यदि ColumnGapRule को 3 (\"Exactly\") पर सेट किया जाता है, तो इकाई को टविप्स (एक पॉइंट का 1/20वाँ) के रूप में व्याख्यायित किया जाता है। यदि ColumnGapRule को 4 (\"Multiple\") पर सेट किया जाता है, तो इकाई को 0.5 इम इंक्रीमेंट की संख्या के रूप में व्याख्यायित किया जाता है। अन्य मामलों में इसे अनदेखा किया जाता है। डिफ़ॉल्ट: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## टिप्पणी

उदाहरण:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## संबंधित देखें

* क्लास [IMathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)