---
title: set_VerticalJustification()
second_title: Aspose.Slides for C++ API 參考手冊
description: "群組字元的垂直對齊方式。指定物件相對於基線的對齊方式。例如，當群組字元位於物件上方時，VerticalJustification 設為 Top 表示物件的頂部落在基線上；當 VerticalJustification 設為 Bottom 時，物件的底部位於基線上。預設值：Bottom for Position=Top, and Top for Position=Bottom"
type: docs
weight: 79
url: /zh-hant/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) 方法

群組字元的垂直對齊方式。指定物件相對於基線的對齊方式。例如，當群組字元位於物件上方時，VerticalJustification 設為 Top 表示物件的頂部落在基線上；當 VerticalJustification 設為 Bottom 時，物件的底部位於基線上。預設值：Bottom for Position=Top, and Top for Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## 備註


範例： 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## 參見

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Class [IMathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)