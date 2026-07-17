---
title: Divide()
second_title: Aspose.Slides for C++ API 参考
description: 使用此分子和指定的分母创建一个分数
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) method

使用此分子和指定的分母创建一个分数

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 分母 |

### 返回值

新分数

## 备注



示例: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) method

使用此分子和指定的分母创建一个分数

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | 分母 |

### 返回值

新分数

## 备注



示例: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) method

使用此分子和指定的分母创建指定类型的分数

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 分母 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 分数类型： Bar, NoBar, Skewed, Linear |

### 返回值

新分数

## 备注



示例: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) method

使用此分子和指定的分母创建指定类型的分数

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | 分母 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 分数类型： Bar, NoBar, Skewed, Linear |

### 返回值

新分数

## 备注



示例: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## 另请参见

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)