---
title: CreateMathFraction()
second_title: Aspose.Slides for C++ API リファレンス
description: 数式分数を作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathfractionfactory/createmathfraction/
---
## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) メソッド

数式分数を作成します

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分子 |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分母 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 分数の種類 |

### 戻り値

新しい数式分数 [IMathFraction](../../imathfraction/)

## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) メソッド

数式分数を作成します

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分子 |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分母 |

### 戻り値

新しい数式分数 [IMathFraction](../../imathfraction/)

## 参照

* 列挙体 [MathFractionTypes](../../mathfractiontypes/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathFraction](../../imathfraction/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathFractionFactory](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)