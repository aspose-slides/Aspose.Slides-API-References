---
title: get_RowSpacing()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "Array की पंक्तियों के बीच अंतराल। यह केवल तब उपयोग किया जाता है जब RowSpacingRule को 3 पर सेट किया गया हो, ठीक उस स्थिति में माप की इकाई points होती है या Multiple में माप की इकाई आधी-लाइनें होती है। डिफ़ॉल्ट: 0"
type: docs
weight: 118
url: /hi/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() विधि

Array की पंक्तियों के बीच का अंतराल। यह केवल तभी उपयोग किया जाता है जब RowSpacingRule को 3 पर सेट किया गया हो, ठीक उस स्थिति में माप की इकाई points होती है, या Multiple जब माप की इकाई आधी-लाइनें होती है। डिफ़ॉल्ट: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## देखें

* क्लास [MathArray](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)