---
title: IMathLimitFactory
second_title: Aspose.Slides for Java API Reference
description: 允许创建 IMathLimit
type: docs
url: /zh/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

允许创建 IMathLimit

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | 创建 IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 在底部创建 IMathLimit |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

创建 IMathLimit

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用限制的基准参数 |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 限制元素 |
| upperLimit | boolean | 设置限制位于顶部 |

**返回:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新的数学限制
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

在底部创建 IMathLimit

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用限制的基准参数 |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 限制元素 |

**返回:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新的数学限制