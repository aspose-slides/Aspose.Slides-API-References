---
title: set_VerticalJustification()
second_title: Aspose.Slides for C++ API 參考文件
description: "群組字符的垂直對齊方式。指定物件相對於基線的對齊。舉例來說，當群組字符位於物件之上時，VerticalJustification 為 Top 表示物件的頂部位於基線上；當 VerticalJustification 設為 Bottom 時，物件的底部位於基線上。預設：Position=Top 時為 Bottom，Position=Bottom 時為 Top"
type: docs
weight: 79
url: /zh-hant/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) method


群組字符的垂直對齊方式。指定物件相對於基線的對齊方式。例如，當群組字符位於物件之上時，VerticalJustification 為 Top 表示物件的頂部位於基線上；當 VerticalJustification 設為 Bottom 時，物件的底部位於基線上。預設：Position=Top 時為 Bottom，Position=Bottom 時為 Top

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## 備註


範例：
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## 另請參閱

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)