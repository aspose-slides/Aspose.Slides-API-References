---
title: Group()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用底部大括號將此元素放入群組
type: docs
weight: 235
url: /zh-hant/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() 方法


使用底部大括號將此元素放入群組

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```


### 返回值

[IMathGroupingCharacter](../../imathgroupingcharacter/) 型別的新實例
## 備註



範例： 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) 方法


使用分組字符（例如底部大括號或其他）將此元素放入群組

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| character | char16_t | 分組字符，例如底部大括號 (U+23DF) 或任何其他 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 分組字符的位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 群組字符的垂直對齊方式。指定物件相對於基線的對齊方式。例如，當群組字符位於物件上方時，VerticalJustification 設為 Top 表示物件的頂部落在基線上；當 VerticalJustification 設為 Bottom 時，物件的底部落在基線上 |

### 返回值

[IMathGroupingCharacter](../../imathgroupingcharacter/) 型別的新實例
## 備註



範例： 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## 另見

* 列舉 [MathTopBotPositions](../../mathtopbotpositions/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathGroupingCharacter](../../imathgroupingcharacter/)
* 類別 [MathElementBase](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)