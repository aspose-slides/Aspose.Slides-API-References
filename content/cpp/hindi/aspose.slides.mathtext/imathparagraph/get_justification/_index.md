---
title: get_Justification()
second_title: Aspose.Slides for C++ API संदर्भ
description: "पैराग्राफ जस्टिफ़िकेशन डिफ़ॉल्ट मान: CenteredAsGroup"
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() विधि


[Paragraph](../../../aspose.slides/paragraph/) Justification डिफ़ॉल्ट मान: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
```

## टिप्पणी


उदाहरण: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## संबंधित देखें

* एन्यूम [MathJustification](../../mathjustification/)
* क्लास [IMathParagraph](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)