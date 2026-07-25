---
title: Divide()
second_title: Aspose.Slides for C++ API リファレンス
description: この分子と指定された分母で分数を作成します
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) メソッド

この分子と指定された分母で分数を作成します

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 分母 |

### 戻り値

新しい分数
## 備考

例: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) メソッド

この分子と指定された分母で分数を作成します

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
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
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) メソッド

この分子と指定された分母で、指定されたタイプの分数を作成します

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 分母 |
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

## IMathElement::Divide(System::String, MathFractionTypes) メソッド

この分子と指定された分母で、指定されたタイプの分数を作成します

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
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

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)