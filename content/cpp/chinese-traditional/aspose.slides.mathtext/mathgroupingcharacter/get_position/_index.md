---
title: get_Position()
second_title: Aspose.Slides for C++ API 參考手冊
description: "分組字元的位置。預設：底部"
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/mathgroupingcharacter/get_position/
---
## MathGroupingCharacter::get_Position() 方法


分組字元的位置。預設：底部

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_Position() override
```

## 備註


範例： 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## 參見

* 列舉 [MathTopBotPositions](../../mathtopbotpositions/)
* 類別 [MathGroupingCharacter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)