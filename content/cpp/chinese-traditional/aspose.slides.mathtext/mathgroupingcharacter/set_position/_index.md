---
title: set_Position()
second_title: Aspose.Slides for C++ API 參考
description: "群組字元的位置。預設：Bottom"
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_position/
---
## MathGroupingCharacter::set_Position(MathTopBotPositions) 方法


群組字元的位置。預設：Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_Position(MathTopBotPositions value) override
```

## 備註


範例：
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## 另請參閱

* 枚舉 [MathTopBotPositions](../../mathtopbotpositions/)
* 類別 [MathGroupingCharacter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)