---
title: get_Justification()
second_title: Aspose.Slides の C++ API リファレンス
description: "Paragraph 整列 デフォルト値: CenteredAsGroup"
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() メソッド


[Paragraph](../../../aspose.slides/paragraph/) Justification デフォルト値: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
```

## 備考


例: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## 参照

* 列挙型 [MathJustification](../../mathjustification/)
* クラス [IMathParagraph](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)