---
title: set_Position()
second_title: Aspose.Slides for C++ API 參考
description: "分組字元的位置。預設：Bottom"
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/imathgroupingcharacter/set_position/
---
## IMathGroupingCharacter::set_Position(MathTopBotPositions) 方法


分組字元的位置。預設：Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Position(MathTopBotPositions value)=0
```

## 備註


範例：
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## 參見

* 列舉 [MathTopBotPositions](../../mathtopbotpositions/)
* 類別 [IMathGroupingCharacter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)