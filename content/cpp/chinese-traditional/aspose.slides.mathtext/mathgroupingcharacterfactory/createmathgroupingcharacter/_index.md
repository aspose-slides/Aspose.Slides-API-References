---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides C++ API 參考
description: 建立一個數學分組字符
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) 方法


建立一個數學分組字符

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用於套用分組字符的數學元素 |
| character | char16_t | 分組字符 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 分組字符的位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 垂直對齊方式 |

### 返回值

新的分組字符元素

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) 方法


建立一個數學分組字符

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用於套用分組字符的數學元素 |

### 返回值

新的分組字符元素

## 另見

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathGroupingCharacter](../../imathgroupingcharacter/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathGroupingCharacterFactory](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)