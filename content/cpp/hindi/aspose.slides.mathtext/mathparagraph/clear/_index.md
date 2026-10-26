---
title: Clear()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह से सभी तत्वों को हटाता है।
type: docs
weight: 79
url: /hi/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() मेथड


संग्रह से सभी तत्वों को हटाता है।

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## संबंधित देखें

* क्लास [MathParagraph](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)