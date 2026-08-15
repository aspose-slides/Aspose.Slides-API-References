---
title: set_Justification()
second_title: Aspose.Slides for C++ API 參考
description: "Paragraph Justification 預設值: CenteredAsGroup"
type: docs
weight: 14
url: /zh-hant/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) 方法


[Paragraph](../../../aspose.slides/paragraph/) 對齊 預設值: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
```

## 備註


範例: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## 另請參見

* 列舉 [MathJustification](../../mathjustification/)
* 類別 [IMathParagraph](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)