---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math delimiter
type: docs
url: /zh/com.aspose.slides/imathdelimiterfactory/
---
```
public interface IMathDelimiterFactory
```

允许创建数学分隔符

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Create a math delimiter by applying to the element |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Create a math delimiter by applying to the element |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

通过对元素应用来创建数学分隔符

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用分隔符的数学元素 |

**返回值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新的数学分隔符
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

通过对元素应用来创建数学分隔符

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 用于应用分隔符的数学元素 |

**返回值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新的数学分隔符