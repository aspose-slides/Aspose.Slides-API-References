---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides for C++ API リファレンス
description: 数式のグルーピング文字を作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) メソッド

数式のグルーピング文字を作成します

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
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

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) メソッド

数式のグルーピング文字を作成します

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | グルーピング文字を適用する数式要素 |

### 戻り値

新しいグルーピング文字要素

## 参照

* 列挙型 [MathTopBotPositions](../../mathtopbotpositions/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathGroupingCharacter](../../imathgroupingcharacter/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathGroupingCharacterFactory](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)