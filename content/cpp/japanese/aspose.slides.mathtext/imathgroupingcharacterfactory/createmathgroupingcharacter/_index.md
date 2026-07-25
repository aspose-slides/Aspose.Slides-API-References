---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides for C++ API リファレンス
description: 数式のグルーピング文字を作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) メソッド


Creates a math grouping character

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | グルーピング文字を適用する数式要素 |
| character | char16_t | グルーピング文字 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | グルーピング文字の位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 垂直方向の配置 |

### 戻り値

新しいグルーピング文字要素

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) メソッド


Creates a math grouping character

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | グルーピング文字を適用する数式要素 |

### 戻り値

新しいグルーピング文字要素

## 関連項目

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../../imathelement/)
* Class [IMathGroupingCharacterFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)