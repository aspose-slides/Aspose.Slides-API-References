---
title: Clear()
second_title: Aspose.Slides for C++ API 参考
description: 从集合中移除所有元素。
type: docs
weight: 79
url: /zh/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() 方法

从集合中移除所有元素。

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## 备注

示例：
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## 另请参见

* 类 [MathParagraph](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)