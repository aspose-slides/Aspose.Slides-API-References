---
title: Divide()
second_title: Aspose.Slides for C++ API リファレンス
description: この分子と指定された分母で分数を作成します
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) メソッド


この分子と指定された分母で分数を作成します

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分母 |

### 戻り値

新しい分数
## 備考



例: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) メソッド


この分子と指定された分母で分数を作成します

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | 分母 |

### 戻り値

新しい分数
## 備考



例: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) メソッド


この分子と指定された分母で指定されたタイプの分数を作成します

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分母 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 分数タイプ: Bar, NoBar, Skewed, Linear |

### 戻り値

新しい分数
## 備考



例: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) メソッド


この分子と指定された分母で指定されたタイプの分数を作成します

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | 分母 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 分数タイプ: Bar, NoBar, Skewed, Linear |

### 戻り値

新しい分数
## 備考



例: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## 参照

* 列挙 [MathFractionTypes](../../mathfractiontypes/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathFraction](../../imathfraction/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathElementBase](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)