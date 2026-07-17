---
title: get_VerticalJustification()
second_title: Aspose.Slides C++ API 参考
description: "垂直对齐的分组字符。指定对象相对于基线的对齐方式。例如，当分组字符位于对象上方时，VerticalJustification 为 Top 表示对象的顶部位于基线；当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线。默认值：Position 为 Top 时为 Bottom，Position 为 Bottom 时为 Top"
type: docs
weight: 66
url: /zh/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() 方法

垂直对齐的分组字符。指定对象相对于基线的对齐方式。例如，当分组字符位于对象上方时，VerticalJustification 为 Top 表示对象的顶部位于基线；当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线。默认值：Position 为 Top 时为 Bottom，Position 为 Bottom 时为 Top

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## 备注

示例：
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## 另请参见

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* 类 [IMathGroupingCharacter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)