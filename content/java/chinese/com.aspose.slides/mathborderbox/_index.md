---
title: MathBorderBox
second_title: Aspose.Slides for Java API 参考
description: 在 IMathElement 周围绘制矩形或其他类型的边框。
type: docs
url: /zh/com.aspose.slides/mathborderbox/
---
**继承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**已实现的接口：**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

在 IMathElement 周围绘制矩形或其他类型的边框。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | 创建带有矩形边框的 MathBorderBox 元素 |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 创建 MathBorderBox 元素 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基础参数 |
| [getHideTop()](#getHideTop--) | 隐藏顶部边缘（默认值为 false）- 指定边框框的顶部边缘的隐藏或显示状态。 |
| [setHideTop(boolean value)](#setHideTop-boolean-) | 隐藏顶部边缘（默认值为 false）- 指定边框框的顶部边缘的隐藏或显示状态。 |
| [getHideBottom()](#getHideBottom--) | 隐藏底部边缘（默认值为 false）- 指定边框框的底部边缘的隐藏或显示状态。 |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | 隐藏底部边缘（默认值为 false）- 指定边框框的底部边缘的隐藏或显示状态。 |
| [getHideLeft()](#getHideLeft--) | 隐藏左侧边缘（默认值为 false）- 指定边框框的左侧边缘的隐藏或显示状态。 |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | 隐藏左侧边缘（默认值为 false）- 指定边框框的左侧边缘的隐藏或显示状态。 |
| [getHideRight()](#getHideRight--) | 隐藏右侧边缘（默认值为 false）- 指定边框框的右侧边缘的隐藏或显示状态。 |
| [setHideRight(boolean value)](#setHideRight-boolean-) | 隐藏右侧边缘（默认值为 false）- 指定边框框的右侧边缘的隐藏或显示状态。 |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | 水平删除线（默认值为 false）- 指定水平删除线的隐藏或显示状态。 |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | 水平删除线（默认值为 false）- 指定水平删除线的隐藏或显示状态。 |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | 垂直删除线（默认值为 false）- 指定垂直删除线的隐藏或显示状态。 |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | 垂直删除线（默认值为 false）- 指定垂直删除线的隐藏或显示状态。 |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | 从左下到右上删除线（默认值为 false）。 |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | 从左下到右上删除线（默认值为 false）。 |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | 从左上到右下删除线（默认值为 false）。 |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | 从左上到右下删除线（默认值为 false）。 |
| [getChildren()](#getChildren--) | 获取子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字符属性 |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

创建带有矩形边框的 MathBorderBox 元素

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 应用边框框的基础元素。可以为 null。 |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

创建 MathBorderBox 元素

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 应用边框框的基础元素 |
| hideTop | boolean | 隐藏顶部边缘 |
| hideBottom | boolean | 隐藏底部边缘 |
| hideLeft | boolean | 隐藏左侧边缘 |
| hideRight | boolean | 隐藏右侧边缘 |
| strikethroughHorizontal | boolean | 水平删除线 |
| strikethroughVertical | boolean | 垂直删除线 |
| strikethroughBottomLeftToTopRight | boolean | 从左下到右上删除线 |
| strikethroughTopLeftToBottomRight | boolean | 从左上到右下删除线 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

基础参数

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

隐藏顶部边缘（默认值为 false）- 指定边框框的顶部边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**返回值：**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

隐藏顶部边缘（默认值为 false）- 指定边框框的顶部边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

隐藏底部边缘（默认值为 false）- 指定边框框的底部边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**返回值：**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

隐藏底部边缘（默认值为 false）- 指定边框框的底部边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

隐藏左侧边缘（默认值为 false）- 指定边框框的左侧边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**返回值：**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

隐藏左侧边缘（默认值为 false）- 指定边框框的左侧边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  }

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

隐藏右侧边缘（默认值为 false）- 指定边框框的右侧边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**返回值：**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

隐藏右侧边缘（默认值为 false）- 指定边框框的右侧边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  }

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

水平删除线（默认值为 false）- 指定水平删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**返回值：**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

水平删除线（默认值为 false）- 指定水平删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  }

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

垂直删除线（默认值为 false）- 指定垂直删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**返回值：**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

垂直删除线（默认值为 false）- 指定垂直删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  }

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

从左下到右上删除线（默认值为 false）。指定从左下角到右上角的对角删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**返回值：**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

从左下到右上删除线（默认值为 false）。指定从左下角到右上角的对角删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  }

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

从左上到右下删除线（默认值为 false）。指定从左上角到右下角的对角删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**返回值：**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

从左上到右下删除线（默认值为 false）。指定从左上角到右下角的对角删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  }

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

获取子元素

**返回值：**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

控制字符属性

**返回值：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps