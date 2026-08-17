---
title: MathBarFactory
second_title: Aspose.Slides for Java API 参考
description: 允许创建数学横线
type: docs
url: /zh/com.aspose.slides/mathbarfactory/
---
**继承：**
java.lang.Object

**所有已实现的接口：**
[com.aspose.slides.IMathBarFactory](../../com.aspose.slides/imathbarfactory)
```
public class MathBarFactory implements IMathBarFactory
```

允许创建数学横线

--------------------

为 COM 兼容性
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathBarFactory()](#MathBarFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | 通过应用于元素创建数学横线 |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | 通过应用于元素创建数学横线 |
### MathBarFactory() {#MathBarFactory--}
```
public MathBarFactory()
```


### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public final IMathBar createMathBar(IMathElement element)
```


通过应用于元素创建数学横线

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要应用横线的数学元素 |

**返回值：**
[IMathBar](../../com.aspose.slides/imathbar) - 新的数学横线元素
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public final IMathBar createMathBar(IMathElement element, int position)
```


通过应用于元素创建数学横线

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要应用横线的数学元素 |
| position | int | 横线的位置 |

**返回值：**
[IMathBar](../../com.aspose.slides/imathbar) - 新的数学横线元素