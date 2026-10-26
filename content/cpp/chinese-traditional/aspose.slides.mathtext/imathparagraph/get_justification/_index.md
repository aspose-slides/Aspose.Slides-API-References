---
title: get_Justification()
second_title: Aspose.Slides for C++ API 參考
description: "段落對齊 預設值：CenteredAsGroup"
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() method


[Paragraph](../../../aspose.slides/paragraph/) Justification 預設值：CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
```

## 備註


範例： 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## 另請參閱

* 列舉 [MathJustification](../../mathjustification/)
* 類別 [IMathParagraph](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)