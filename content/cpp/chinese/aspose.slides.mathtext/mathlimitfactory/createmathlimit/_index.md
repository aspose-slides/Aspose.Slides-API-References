---
title: CreateMathLimit()
second_title: Aspose.Slides for C++ API 参考
description: 创建 IMathLimit
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) 方法

创建 [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用于应用限制的基参数 |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 限制元素 |
| upperLimit | **bool** | 设置限制置于顶部 |

### 返回值

新的数学限制

## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 方法

创建 [IMathLimit](../../imathlimit/)，限制位于底部

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用于应用限制的基参数 |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 限制元素 |

### 返回值

新的数学限制

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathLimit](../../imathlimit/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathLimitFactory](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)