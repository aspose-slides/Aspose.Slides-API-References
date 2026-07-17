---
title: CreateMathFraction()
second_title: Aspose.Slides C++ API 参考
description: 创建一个数学分数
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathfractionfactory/createmathfraction/
---
## MathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) method

创建一个数学分数

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分子 |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分母 |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | 分数类型 |

### 返回值



## MathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

创建一个数学分数

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分子 |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 分母 |

### 返回值



## 另请参见

* 枚举 [MathFractionTypes](../../mathfractiontypes/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathFraction](../../imathfraction/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathFractionFactory](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)