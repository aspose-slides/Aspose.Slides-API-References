---
title: Integral()
second_title: Aspose.Slides for C++ API 参考
description: 获取积分
type: docs
weight: 196
url: /zh/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) 方法

获取积分

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 积分类型 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 积分的下限 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 积分的上限 |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | 限制位置 |

### 返回值

类型为 [IMathNaryOperator](../../imathnaryoperator/) 的新实例

## 备注



示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 方法

获取积分

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 积分类型 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 积分的下限 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 积分的上限 |

### 返回值

类型为 [IMathNaryOperator](../../imathnaryoperator/) 的新实例

## 备注



示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) 方法

获取积分（无上下限）

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 积分类型 |

### 返回值

类型为 [IMathNaryOperator](../../imathnaryoperator/) 的新实例

## 备注



示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) 方法

获取积分

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 积分类型 |
| lowerLimit | [System::String](../../../system/string/) | 积分的下限 |
| upperLimit | [System::String](../../../system/string/) | 积分的上限 |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | 限制位置 |

### 返回值

类型为 [IMathNaryOperator](../../imathnaryoperator/) 的新实例

## 备注



示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) 方法

获取积分

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 积分类型 |
| lowerLimit | [System::String](../../../system/string/) | 积分的下限 |
| upperLimit | [System::String](../../../system/string/) | 积分的上限 |

### 返回值

类型为 [IMathNaryOperator](../../imathnaryoperator/) 的新实例

## 备注



示例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## 另见

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)