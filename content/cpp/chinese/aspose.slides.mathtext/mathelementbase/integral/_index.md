---
title: Integral()
second_title: Aspose.Slides for C++ API 参考
description: 计算积分
type: docs
weight: 183
url: /zh/aspose.slides.mathtext/mathelementbase/integral/
---
## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) 方法

计算积分

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 积分类型 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 积分的下限 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 积分的上限 |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | 限值的位置 |

### 返回值

类型为 [IMathNaryOperator](../../imathnaryoperator/) 的新实例

## 备注

```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 方法

计算积分

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 积分类型 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 积分的下限 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 积分的上限 |

### 返回值

类型为 [IMathNaryOperator](../../imathnaryoperator/) 的新实例

## 备注

```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"?\?");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes) 方法

在没有上下限的情况下计算积分

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 积分类型 |

### 返回值

类型为 [IMathNaryOperator](../../imathnaryoperator/) 的新实例

## 备注

```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) 方法

计算积分

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | 积分类型 |
| lowerLimit | [System::String](../../../system/string/) | 积分的下限 |
| upperLimit | [System::String](../../../system/string/) | 积分的上限 |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | 限值的位置 |

### 返回值

类型为 [IMathNaryOperator](../../imathnaryoperator/) 的新实例

## 备注

```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String) 方法

计算积分

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit) override
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

```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## 另请参见

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathNaryOperator](../../imathnaryoperator/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathElementBase](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)