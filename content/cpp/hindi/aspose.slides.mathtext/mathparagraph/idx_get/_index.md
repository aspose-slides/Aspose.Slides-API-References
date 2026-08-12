---
title: idx_get()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट अनुक्रमांक पर वस्तु को प्राप्त करता है। केवल-पढ़ने योग्य IMathBlock.
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/mathparagraph/idx_get/
---
## MathParagraph::idx_get(int32_t) method


निर्दिष्ट अनुक्रमांक पर वस्तु को प्राप्त करता है। केवल-पढ़ने योग्य [IMathBlock](../../imathblock/).

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathParagraph::idx_get(int32_t index) override
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | प्राप्त करने वाली वस्तु का शून्य-आधारित अनुक्रमांक |

### वापसी मान

गणितीय पाठ का ब्लॉक.
## टिप्पणियाँ



उदाहरण: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../../imathblock/)
* क्लास [MathParagraph](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)