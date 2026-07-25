---
title: CreateMathFraction()
second_title: Aspose.Slides for C++ API リファレンス
description: 数式分数を作成します
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathfractionfactory/createmathfraction/
---
## MathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) メソッド

数式分数を作成します

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分子 |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分母 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 分数タイプ |

### 戻り値



## MathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) メソッド

数式分数を作成します

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分子 |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分母 |

### 戻り値



## 参照

* 列挙型 [MathFractionTypes](../../mathfractiontypes/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathFraction](../../imathfraction/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathFractionFactory](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)