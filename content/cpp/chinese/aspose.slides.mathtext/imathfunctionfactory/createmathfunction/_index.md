---
title: CreateMathFunction()
second_title: Aspose.Slides C++ API 参考
description: 创建数学函数
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 方法

创建数学函数

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用作函数名的元素 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用作函数参数的元素 |

### 返回值

新数学函数

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) 方法

创建数学函数

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | 函数名 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用作函数参数的元素 |

### 返回值

新数学函数

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathFunction](../../imathfunction/)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathFunctionFactory](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)