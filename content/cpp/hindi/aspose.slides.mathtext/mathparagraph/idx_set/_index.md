---
title: idx_set()
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: निर्दिष्ट सूचकांक पर आइटम प्राप्त करता है। केवल-पढ़ने योग्य IMathBlock।
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/mathparagraph/idx_set/
---
## MathParagraph::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) विधि

निर्दिष्ट सूचकांक पर आइटम प्राप्त करता है। केवल-पढ़ने योग्य [IMathBlock](../../imathblock/).

```cpp
void Aspose::Slides::MathText::MathParagraph::idx_set(int32_t index, System::SharedPtr<IMathBlock> value) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | प्राप्त करने वाले आइटम का शून्य-आधारित सूचकांक |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | गणितीय पाठ का ब्लॉक। |
## टिप्पणियाँ



उदाहरण: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## सम्बन्धित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../../imathblock/)
* क्लास [MathParagraph](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)