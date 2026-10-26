---
title: Integral()
second_title: Aspose.Slides for C++ API リファレンス
description: 積分を取得します
type: docs
weight: 183
url: /ja/aspose.slides.mathtext/mathelementbase/integral/
---
## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) メソッド

積分を取得します

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 積分の種類 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 積分の下限 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 積分の上限 |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | リミットの位置 |

### 戻り値

型[IMathNaryOperator](../../imathnaryoperator/)の新しいインスタンス
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) メソッド

積分を取得します

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 積分の種類 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 積分の下限 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 積分の上限 |

### 戻り値

型[IMathNaryOperator](../../imathnaryoperator/)の新しいインスタンス
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"?\?");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes) メソッド

上限と下限なしで積分を取得します

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 積分の種類 |

### 戻り値

型[IMathNaryOperator](../../imathnaryoperator/)の新しいインスタンス
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) メソッド

積分を取得します

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 積分の種類 |
| lowerLimit | [System::String](../../../system/string/) | 積分の下限 |
| upperLimit | [System::String](../../../system/string/) | 積分の上限 |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | リミットの位置 |

### 戻り値

型[IMathNaryOperator](../../imathnaryoperator/)の新しいインスタンス
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String) メソッド

積分を取得します

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 積分の種類 |
| lowerLimit | [System::String](../../../system/string/) | 積分の下限 |
| upperLimit | [System::String](../../../system/string/) | 積分の上限 |

### 戻り値

型[IMathNaryOperator](../../imathnaryoperator/)の新しいインスタンス
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## 参照

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)