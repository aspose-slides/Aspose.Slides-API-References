---
title: CreateMathAccent()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された数式要素にデフォルトのアクセント文字を適用した数式アクセントを作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) メソッド

指定された数式要素にデフォルトのアクセント文字を適用した数式アクセントを作成します

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | アクセントを適用する数式要素 |

### 戻り値

新しい数式アクセント

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) メソッド

指定された数式要素にアクセントを適用した数式アクセントを作成します

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | アクセントを適用する数式要素 |
| accentCharacter | char16_t | アクセント文字 |

### 戻り値

新しい数式アクセント

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathAccent](../../imathaccent/)
* Class [IMathElement](../../imathelement/)
* Class [IMathAccentFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)