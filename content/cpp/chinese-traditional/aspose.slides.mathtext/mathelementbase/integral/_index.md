---
title: Integral()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得積分
type: docs
weight: 183
url: /zh-hant/aspose.slides.mathtext/mathelementbase/integral/
---
## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) 方法

取得積分

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit of integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upper limit of integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | location of limits |

### 傳回值

型別 [IMathNaryOperator](../../imathnaryoperator/) 的新執行個體

## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 方法


取得積分

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit of integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upper limit of integral |

### 傳回值

型別 [IMathNaryOperator](../../imathnaryoperator/) 的新執行個體

## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"?\?");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes) 方法


取得無限制的積分

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |

### 傳回值

型別 [IMathNaryOperator](../../imathnaryoperator/) 的新執行個體

## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) 方法


取得積分

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::String](../../../system/string/) | Lower limit of integral |
| upperLimit | [System::String](../../../system/string/) | Upper limit of integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | location of limits |

### 傳回值

型別 [IMathNaryOperator](../../imathnaryoperator/) 的新執行個體

## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String) 方法


取得積分

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Integral type |
| lowerLimit | [System::String](../../../system/string/) | Lower limit of integral |
| upperLimit | [System::String](../../../system/string/) | Upper limit of integral |

### 傳回值

型別 [IMathNaryOperator](../../imathnaryoperator/) 的新執行個體

## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## 參見

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)