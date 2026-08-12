---
title: set_RowSpacing()
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक array की पंक्तियों के बीच की दूरी। यह केवल तब उपयोग किया जाता है जब RowSpacingRule को 3 पर सेट किया गया हो, बिल्कुल उसी मामले में माप की इकाई points होती है या Multiple में, जहाँ माप की इकाई आधी-लाइन होती है। डिफ़ॉल्ट: 0"
type: docs
weight: 131
url: /hi/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) मेथड

एक array की पंक्तियों के बीच की दूरी। यह केवल तब उपयोग किया जाता है जब RowSpacingRule को 3 पर सेट किया गया हो, बिल्कुल उसी मामले में माप की इकाई points होती है या Multiple में, जहाँ माप की इकाई आधी-लाइन होती है। डिफ़ॉल्ट: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## देखें भी

* वर्ग [MathArray](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)