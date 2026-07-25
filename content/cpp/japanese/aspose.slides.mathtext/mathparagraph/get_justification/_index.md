---
title: get_Justification()
second_title: Aspose.Slides for C++ API リファレンス
description: "Paragraph Justification デフォルト値: CenteredAsGroup"
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() メソッド

[Paragraph](../../../aspose.slides/paragraph/) Justification デフォルト値: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## 備考

例: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## 参照

* Enum [MathJustification](../../mathjustification/)
* クラス [MathParagraph](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)