---
title: set_Justification()
second_title: Aspose.Slides for C++ API 참조
description: "문단 정렬 기본값: CenteredAsGroup"
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) 메서드


[Paragraph](../../../aspose.slides/paragraph/) Justification 기본값: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
```

## 비고


예제: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## 참고

* 열거형 [MathJustification](../../mathjustification/)
* 클래스 [IMathParagraph](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)