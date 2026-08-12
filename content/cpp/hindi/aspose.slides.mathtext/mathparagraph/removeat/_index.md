---
title: RemoveAt()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह में निर्दिष्ट अनुक्रमणिका पर आइटम को हटाता है।
type: docs
weight: 157
url: /hi/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(int32_t) विधि

संग्रह में निर्दिष्ट अनुक्रमणिका पर आइटम को हटाता है।

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | वह शून्य-आधारित index है जिसे हटाया जाना है। |
## टिप्पणियाँ



उदाहरण: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## संदर्भ

* क्लास [MathParagraph](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)