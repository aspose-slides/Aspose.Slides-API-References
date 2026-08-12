---
title: get_Justification()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "Paragraph Justification डिफ़ॉल्ट मान: CenteredAsGroup"
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() विधि

[Paragraph](../../../aspose.slides/paragraph/) Justification डिफ़ॉल्ट मान: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## संबंधित देखें

* एन्यूम [MathJustification](../../mathjustification/)
* क्लास [MathParagraph](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)