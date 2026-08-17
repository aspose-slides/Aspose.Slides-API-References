---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math delimiter
type: docs
url: /zh/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

允许创建数学分隔符

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | 创建数学分隔符，通过将其应用于元素 |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | 创建数学分隔符，通过将其应用于元素 |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

通过将分隔符应用于元素来创建数学分隔符

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要应用分隔符的数学元素 |

**返回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新的数学分隔符
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

通过将分隔符应用于元素来创建数学分隔符

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 要应用分隔符的数学元素集合 |

**返回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新的数学分隔符