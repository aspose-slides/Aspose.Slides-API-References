---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個數學分組字元
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) 方法

建立一個數學分組字元

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用分組字元的數學元素 |
| character | char16_t | 分組字元 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 分組字元的位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 垂直對齊 |

### 返回值

新的分組字元元素

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) 方法

建立一個數學分組字元

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用分組字元的數學元素 |

### 返回值

新的分組字元元素

## 另請參閱

* 列舉 [MathTopBotPositions](../../mathtopbotpositions/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathGroupingCharacter](../../imathgroupingcharacter/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathGroupingCharacterFactory](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)