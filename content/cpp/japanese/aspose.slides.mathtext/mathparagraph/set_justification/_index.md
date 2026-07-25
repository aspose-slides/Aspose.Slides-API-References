---
title: set_Justification()
second_title: Aspose.Slides for C++ API リファレンス
description: "段落の配置 デフォルト値: CenteredAsGroup"
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) メソッド


[Paragraph](../../../aspose.slides/paragraph/) Justification デフォルト値: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
```

## 備考


例: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## 関連項目

* 列挙型 [MathJustification](../../mathjustification/)
* クラス [MathParagraph](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)