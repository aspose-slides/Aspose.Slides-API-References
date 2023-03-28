---
title: set_Justification()
second_title: Aspose.Slides for C++ API Reference
description: "Paragraph Justification Default value: CenteredAsGroup"
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification([MathJustification](../../mathjustification/)) method


[Paragraph](../../../aspose.slides/paragraph/) Justification Default value: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
```

## Remarks


Example: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## See Also

* Enum [MathJustification](../../mathjustification/)
* Class [IMathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
