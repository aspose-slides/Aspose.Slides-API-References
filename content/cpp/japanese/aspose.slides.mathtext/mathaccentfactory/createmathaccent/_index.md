---
title: CreateMathAccent()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された数式要素にデフォルトのアクセント文字の値を適用した数式アクセントを作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) method


指定された数式要素にデフォルトのアクセント文字の値を適用した数式アクセントを作成します

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | アクセントを適用する数式要素 |

### 戻り値

新しい数式アクセント

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) method


指定された数式要素にアクセントを適用した数式アクセントを作成します

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```


### 引数

| Parameter | Type | Description |
| --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | アクセントを適用する数式要素 |
| accentCharacter | char16_t | アクセント文字 |

### 戻り値

新しい数式アクセント

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathAccent](../../imathaccent/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathAccentFactory](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)