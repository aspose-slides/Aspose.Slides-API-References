---
title: get_Justification()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Paragraph Justification 기본값: CenteredAsGroup"
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() 메서드


[Paragraph](../../../aspose.slides/paragraph/) Justification 기본값: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## 비고


예시: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## 참조

* 열거형 [MathJustification](../../mathjustification/)
* 클래스 [MathParagraph](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)