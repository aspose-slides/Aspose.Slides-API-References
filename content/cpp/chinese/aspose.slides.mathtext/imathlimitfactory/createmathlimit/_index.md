---
title: CreateMathLimit()
second_title: Aspose.Slides 用于 C++ 的 API 参考
description: 创建 IMathLimit
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) method

创建 [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply the limit |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limit element |
| upperLimit | **bool** | Sets the placement of the limit on top |

### 返回值

新的数学限制

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

创建 [IMathLimit](../../imathlimit/)，并在底部放置限制

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument to apply the limit |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limit element |

### 返回值

新的数学限制

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathLimit](../../imathlimit/)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathLimitFactory](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)