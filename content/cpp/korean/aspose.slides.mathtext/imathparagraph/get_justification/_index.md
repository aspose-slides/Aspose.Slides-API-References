---
title: get_Justification()
second_title: Aspose.Slides for C++ API 참조
description: "Paragraph Justification 기본값: CenteredAsGroup"
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() 메서드

[Paragraph](../../../aspose.slides/paragraph/) Justification 기본값: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
```

## 비고


예제:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## 관련 항목

* Enum [MathJustification](../../mathjustification/)
* 클래스 [IMathParagraph](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)