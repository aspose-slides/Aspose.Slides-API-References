---
title: get_Justification()
second_title: Aspose.Slides for C++ API Reference
description: "Paragraph Justification Default value: CenteredAsGroup"
type: docs
weight: 1
url: /aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() method


[Paragraph](../../../aspose.slides/paragraph/) Justification Default value: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
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
* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)