---
title: Insert()
second_title: Aspose.Slides C++ के लिए एपीआई संदर्भ
description: निर्दिष्ट अनुक्रमांक पर संग्रह में IMathBlock को सम्मिलित करता है।
type: docs
weight: 144
url: /hi/aspose.slides.mathtext/mathparagraph/insert/
---
## MathParagraph::Insert(int32_t, System::SharedPtr\<IMathBlock\>) विधि

[IMathBlock](../../imathblock/) को निर्दिष्ट अनुक्रमांक पर संग्रह में सम्मिलित करता है।

```cpp
void Aspose::Slides::MathText::MathParagraph::Insert(int32_t index, System::SharedPtr<IMathBlock> mathBlock) override
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | वह शून्य-आधारित इंडेक्स जहाँ किसी आइटम को सम्मिलित किया जाना चाहिए। |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | सम्मिलित करने के लिए [IMathBlock](../../imathblock/)। |

## टिप्पणियाँ



उदाहरण: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Insert(0, block);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)