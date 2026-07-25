---
title: set_Justification()
second_title: Aspose.Slides for C++ API リファレンス
description: "Paragraph Justification のデフォルト値: CenteredAsGroup"
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) メソッド

[Paragraph](../../../aspose.slides/paragraph/) Justification デフォルト値：CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
```

## 備考

例:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## 関連項目

* Enum [MathJustification](../../mathjustification/)
* Class [IMathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)