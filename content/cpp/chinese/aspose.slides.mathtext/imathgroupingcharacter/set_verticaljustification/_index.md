---
title: set_VerticalJustification()
second_title: Aspose.Slides for C++ API 参考
description: "组字符的垂直对齐方式。指定对象相对于基线的对齐方式。例如，当组字符位于对象上方时，VerticalJustification 为 Top 表示对象的顶部位于基线上；当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线。默认情况下：Position=Top 时为 Bottom，Position=Bottom 时为 Top"
type: docs
weight: 79
url: /zh/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) 方法

组字符的垂直对齐方式。指定对象相对于基线的对齐方式。例如，当组字符位于对象上方时，VerticalJustification 为 Top 表示对象的顶部位于基线上；当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线。默认情况：Position=Top 时为 Bottom，Position=Bottom 时为 Top。

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## 备注

示例：
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## 另见

* 枚举 [MathTopBotPositions](../../mathtopbotpositions/)
* 类 [IMathGroupingCharacter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)