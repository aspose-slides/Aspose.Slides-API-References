---
title: IndexOf()
second_title: Aspose.Slides के लिये C++ API संदर्भ
description: संग्रह में किसी विशिष्ट IMathBlock का सूचकांक निर्धारित करता है।
type: docs
weight: 131
url: /hi/aspose.slides.mathtext/mathparagraph/indexof/
---
## MathParagraph::IndexOf(System::SharedPtr\<IMathBlock\>) विधि

किसी विशिष्ट [IMathBlock](../../imathblock/) का संग्रह में सूचकांक निर्धारित करता है।

```cpp
int32_t Aspose::Slides::MathText::MathParagraph::IndexOf(System::SharedPtr<IMathBlock> mathBlock) override
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | संग्रह में खोजने के लिये वस्तु। |

### रिटर्न वैल्यू

यदि संग्रह में पाया जाए तो *mathBlock* का सूचकांक; अन्यथा -1.

## टिप्पणियाँ

उदाहरण:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
int32_t index = mathParagraph->IndexOf(block);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../../imathblock/)
* क्लास [MathParagraph](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)