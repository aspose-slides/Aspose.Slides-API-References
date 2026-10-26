---
title: get_RowSpacing()
second_title: Aspose.Slides C++ के लिए API रेफरेंस
description: "एक सरणी की पंक्तियों के बीच अंतराल यह केवल तब उपयोग किया जाता है जब RowSpacingRule को 3 पर सेट किया गया हो। बिल्कुल ऐसी स्थिति में मापन इकाई बिंदु होती है या Multiple स्थिति में मापन इकाई अर्ध-रेखा होती है। डिफॉल्ट: 0"
type: docs
weight: 118
url: /hi/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() विधि

एक सरणी की पंक्तियों के बीच का अंतराल यह केवल तब उपयोग किया जाता है जब RowSpacingRule 3 पर सेट हो। बिल्कुल ऐसी स्थिति में मापन इकाई बिंदु होती है या Multiple स्थिति में मापन इकाई अर्ध-रेखा होती है। Default: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
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
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)