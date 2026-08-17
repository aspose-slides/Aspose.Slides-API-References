---
title: IMathBarFactory
second_title: Aspose.Slides for Java API 参考
description: 允许创建数学横线
type: docs
url: /zh/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

允许创建数学横线

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Create a math bar by applying to the element |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Create a math bar by applying to the element |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```


通过应用到元素来创建数学横线

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用横线的数学元素 |

**返回值：**
[IMathBar](../../com.aspose.slides/imathbar) - 新的数学横线元素
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```


通过应用到元素来创建数学横线

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用横线的数学元素 |
| position | int | 横线的位置 |

**返回值：**
[IMathBar](../../com.aspose.slides/imathbar) - 新的数学横线元素