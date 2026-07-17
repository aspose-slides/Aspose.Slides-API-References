---
title: get_Justification()
second_title: Aspose.Slides for C++ API 参考
description: "段落 对齐方式 默认值: CenteredAsGroup"
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() 方法

[Paragraph](../../../aspose.slides/paragraph/) 对齐方式 默认值： CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
```

## 备注

示例： 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## 另见

* 枚举 [MathJustification](../../mathjustification/)
* 类 [IMathParagraph](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)