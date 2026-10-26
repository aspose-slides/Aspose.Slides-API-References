---
title: MathGroupingCharacter()
second_title: Aspose.Slides for C++ API リファレンス
description: MathGroupingCharacter クラスの新しいインスタンスを、デフォルトのグルーピング文字 U+23DF（BOTTOM CURLY BRACKET）で初期化します
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) コンストラクタ

[MathGroupingCharacter](../) クラスの新しいインスタンスを、デフォルトのグルーピング文字 U+23DF（下カール括弧）で初期化します

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | バーが適用される基本要素 |

## 備考

例: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) コンストラクタ

[MathGroupingCharacter](../) クラスの新しいインスタンスを初期化します

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | バーが適用される基本要素 |
| character | char16_t | グルーピング文字 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | グルーピング文字の位置 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | グループ文字の垂直揃え |

## 備考

例: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## 関連項目

* 列挙型 [MathTopBotPositions](../../mathtopbotpositions/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathGroupingCharacter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)