---
title: IMathBarFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 允许创建数学栏
type: docs
url: /zh/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

允许创建数学栏

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


Create a math bar by applying to the element

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要应用栏的数学元素 |

**返回:**
[IMathBar](../../com.aspose.slides/imathbar) - 新的数学栏元素
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```


Create a math bar by applying to the element

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要应用栏的数学元素 |
| position | int | 栏的位置 |

**返回:**
[IMathBar](../../com.aspose.slides/imathbar) - 新的数学栏元素