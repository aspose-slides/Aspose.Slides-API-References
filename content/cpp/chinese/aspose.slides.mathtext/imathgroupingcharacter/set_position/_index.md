---
title: set_Position()
second_title: Aspose.Slides C++ API 参考
description: "分组字符的位置。默认：Bottom"
type: docs
weight: 53
url: /zh/aspose.slides.mathtext/imathgroupingcharacter/set_position/
---
## IMathGroupingCharacter::set_Position(MathTopBotPositions) 方法

分组字符的位置。默认：Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Position(MathTopBotPositions value)=0
```

## 备注

示例：
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## 另请参见

* 枚举 [MathTopBotPositions](../../mathtopbotpositions/)
* 类 [IMathGroupingCharacter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)