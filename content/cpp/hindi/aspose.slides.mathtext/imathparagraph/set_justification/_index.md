---
title: set_Justification()
second_title: Aspose.Slides C++ के लिए API रेफ़रेंस
description: "Paragraph Justification डिफ़ॉल्ट मान: CenteredAsGroup"
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) मेथड


[Paragraph](../../../aspose.slides/paragraph/) जस्टिफिकेशन डिफ़ॉल्ट मान: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
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
* क्लास [IMathParagraph](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)