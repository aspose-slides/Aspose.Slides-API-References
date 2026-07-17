---
title: set_Justification()
second_title: Aspose.Slides C++ API 参考
description: "Paragraph Justification 默认值: CenteredAsGroup"
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) 方法

[Paragraph](../../../aspose.slides/paragraph/) Justification 默认值：CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
```

## 备注

示例：
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## 另请参阅

* 枚举 [MathJustification](../../mathjustification/)
* 类 [IMathParagraph](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)