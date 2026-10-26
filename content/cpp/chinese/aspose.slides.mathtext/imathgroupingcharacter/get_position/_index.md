---
title: get_Position()
second_title: Aspose.Slides C++ API 参考
description: "分组字符的位置。默认：底部"
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() 方法

分组字符的位置。默认：底部

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## 备注

示例：
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## 另见

* 枚举 [MathTopBotPositions](../../mathtopbotpositions/)
* 类 [IMathGroupingCharacter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)