---
title: MathDelimiterFactory
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 允许创建数学分隔符
type: docs
url: /zh/com.aspose.slides/mathdelimiterfactory/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IMathDelimiterFactory](../../com.aspose.slides/imathdelimiterfactory)
```
public class MathDelimiterFactory implements IMathDelimiterFactory
```

允许创建数学分隔符

--------------------

用于 COM 兼容性
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathDelimiterFactory()](#MathDelimiterFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | 通过应用于元素来创建数学分隔符 |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | 通过应用于元素来创建数学分隔符 |
### MathDelimiterFactory() {#MathDelimiterFactory--}
```
public MathDelimiterFactory()
```


### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public final IMathDelimiter createMathDelimiter(IMathElement element)
```


通过应用于元素来创建数学分隔符

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用分隔符的数学元素 |

**返回值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新的数学分隔符
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public final IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```


通过应用于元素来创建数学分隔符

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 用于应用分隔符的数学元素 |

**返回值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新的数学分隔符