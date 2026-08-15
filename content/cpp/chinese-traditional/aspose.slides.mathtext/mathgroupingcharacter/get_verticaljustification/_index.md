---
title: get_VerticalJustification()
second_title: Aspose.Slides for C++ API 參考
description: "群組字元的垂直對齊方式。指定物件相對於基線的對齊方式。例如，當群組字元位於物件之上時，VerticalJustification 為 Top 表示物件的頂部落在基線上；當 VerticalJustification 設為 Bottom 時，物件的底部落在基線上。預設值：Position=Top 時為 Bottom，Position=Bottom 時為 Top"
type: docs
weight: 66
url: /zh-hant/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() 方法


群組字元的垂直對齊方式。指定物件相對於基線的對齊方式。例如，當群組字元位於物件之上時，VerticalJustification 為 Top 表示物件的頂部落在基線上；當 VerticalJustification 設為 Bottom 時，物件的底部落在基線上。預設值：Position=Top 時為 Bottom，Position=Bottom 時為 Top

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## 備註


範例： 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## 另見

* 列舉 [MathTopBotPositions](../../mathtopbotpositions/)
* 類別 [MathGroupingCharacter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)