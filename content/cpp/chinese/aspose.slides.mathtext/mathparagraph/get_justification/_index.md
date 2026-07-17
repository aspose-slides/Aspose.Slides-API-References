---
title: get_Justification()
second_title: Aspose.Slides for C++ API 参考
description: "段落对齐方式 默认值: CenteredAsGroup"
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() 方法


[Paragraph](../../../aspose.slides/paragraph/) Justification 默认值: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## 备注


示例:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## 另请参见

* Enum [MathJustification](../../mathjustification/)
* 类 [MathParagraph](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)