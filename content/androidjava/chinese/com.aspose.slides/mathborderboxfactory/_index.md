---
title: MathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API 参考
description: 允许创建数学边框盒
type: docs
url: /zh/com.aspose.slides/mathborderboxfactory/
---
**继承：**
java.lang.Object

**所有已实现的接口：**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

允许创建数学边框盒

--------------------

用于 COM 兼容性
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | 通过应用于元素来创建数学边框盒 |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 通过应用于元素来创建数学边框盒 |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


通过应用于元素来创建数学边框盒

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用边框盒的数学元素 |

**返回值：**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新的边框盒元素
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


通过应用于元素来创建数学边框盒

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用边框盒的数学元素 |
| hideTop | boolean | 隐藏顶部边缘 |
| hideBottom | boolean | 隐藏底部边缘 |
| hideLeft | boolean | 隐藏左侧边缘 |
| hideRight | boolean | 隐藏右侧边缘 |
| strikethroughHorizontal | boolean | 水平划线边框盒 |
| strikethroughVertical | boolean | 垂直划线边框盒 |
| strikethroughBottomLeftToTopRight | boolean | 从左下到右上的划线边框盒 |
| strikethroughTopLeftToBottomRight | boolean | 从左上到右下的划线边框盒 |

**返回值：**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新的边框盒元素