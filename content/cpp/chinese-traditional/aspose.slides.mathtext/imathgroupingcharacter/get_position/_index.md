---
title: get_Position()
second_title: Aspose.Slides for C++ API 參考文件
description: "分組字元的位置。預設：底部"
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() 方法

分組字元的位置。預設：底部

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## 備註

範例：
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## 另請參閱

* 列舉 [MathTopBotPositions](../../mathtopbotpositions/)
* 類別 [IMathGroupingCharacter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)