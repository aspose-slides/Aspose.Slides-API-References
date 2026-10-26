---
title: set_Justification()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "단락 정렬 기본값: CenteredAsGroup"
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) 메서드


[Paragraph](../../../aspose.slides/paragraph/) Justification 기본값: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
```

## 비고


예제: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## 참조

* Enum [MathJustification](../../mathjustification/)
* 클래스 [MathParagraph](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)