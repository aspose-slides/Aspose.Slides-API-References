---
title: get_Position()
second_title: Aspose.Slides C++ API 参考
description: "分组字符的位置。默认：底部"
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/mathgroupingcharacter/get_position/
---
## MathGroupingCharacter::get_Position() 方法

分组字符的位置。默认：底部

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_Position() override
```

## 备注

示例： 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## 另请参阅

* 枚举 [MathTopBotPositions](../../mathtopbotpositions/)
* 类 [MathGroupingCharacter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)