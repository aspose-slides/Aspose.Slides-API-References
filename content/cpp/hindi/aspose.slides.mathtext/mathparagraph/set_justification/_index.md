---
title: set_Justification()
second_title: Aspose.Slides C++ API संदर्भ
description: "Paragraph जस्टिफ़िकेशन डिफ़ॉल्ट मान: CenteredAsGroup"
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) विधि

[Paragraph](../../../aspose.slides/paragraph/) Justification डिफ़ॉल्ट मान: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## संबंधित देखें

* Enum [MathJustification](../../mathjustification/)
* क्लास [MathParagraph](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)