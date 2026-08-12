---
title: set_RowSpacing()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "एक सरणी की पंक्तियों के बीच का अंतराल। यह केवल तब उपयोग किया जाता है जब RowSpacingRule को 3 पर सेट किया गया हो। बिल्कुल उसी स्थिति में जहाँ माप की इकाई points है या Multiple जहाँ माप की इकाई आधी-लाइन है। डिफ़ॉल्ट: 0"
type: docs
weight: 131
url: /hi/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) विधि

एक सरणी की पंक्तियों के बीच का अंतराल। यह केवल तब उपयोग किया जाता है जब RowSpacingRule को 3 पर सेट किया गया हो। बिल्कुल उसी स्थिति में जहाँ माप की इकाई points है या Multiple जहाँ माप की इकाई आधी-लाइन है। डिफ़ॉल्ट: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## संबंधित देखें

* क्लास [IMathArray](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* पुस्तकालय [Aspose.Slides](../../../)