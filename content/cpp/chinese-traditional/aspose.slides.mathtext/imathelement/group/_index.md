---
title: Group()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 使用底部大括號將此元素放入群組
type: docs
weight: 248
url: /zh-hant/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() 方法

使用底部大括號將此元素放入群組

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```

### 傳回值

新實例型別 [IMathGroupingCharacter](../../imathgroupingcharacter/)
## 備註



範例：
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) 方法

使用分組字元（例如 BOTTOM CURLY BRACKET (U+23DF) 或任何其他）將此元素放入群組

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| character | char16_t | 用於分組的字元，例如 BOTTOM CURLY BRACKET (U+23DF) 或任何其他 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 分組字元的位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 群組字元的垂直對齊方式。指定物件相對於基線的對齊方式。例如，當群組字元位於物件上方時，VerticalJustification 為 Top 表示物件的頂部落在基線上；當 VerticalJustification 設為 Bottom 時，物件的底部位於基線上 |

### 傳回值

新實例型別 [IMathGroupingCharacter](../../imathgroupingcharacter/)
## 備註



範例：
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## 另見

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)