---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math border box
type: docs
url: /zh/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

允许创建数学边框盒

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | 通过应用于元素来创建数学边框盒 |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 通过应用于元素来创建数学边框盒 |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

通过应用于元素来创建数学边框盒

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要应用边框盒的数学元素 |

**返回值：**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新的边框盒元素
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

通过应用于元素来创建数学边框盒

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要应用边框盒的数学元素 |
| hideTop | boolean | 隐藏顶部边缘 |
| hideBottom | boolean | 隐藏底部边缘 |
| hideLeft | boolean | 隐藏左侧边缘 |
| hideRight | boolean | 隐藏右侧边缘 |
| strikethroughHorizontal | boolean | 边框盒水平删除线 |
| strikethroughVertical | boolean | 边框盒垂直删除线 |
| strikethroughBottomLeftToTopRight | boolean | 边框盒从左下到右上删除线 |
| strikethroughTopLeftToBottomRight | boolean | 边框盒从左上到右下删除线 |

**返回值：**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 新的边框盒元素