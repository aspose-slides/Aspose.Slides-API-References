---
title: CreateMathFunction()
second_title: Aspose.Slides for C++ API 参考
description: 创建数学函数
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 方法

创建数学函数

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用作函数名的元素 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用作函数参数的元素 |

### 返回值

新的数学函数

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) 方法

创建数学函数

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | 函数名 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用作函数参数的元素 |

### 返回值

新的数学函数

## 另见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathFunction](../../imathfunction/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathFunctionFactory](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)