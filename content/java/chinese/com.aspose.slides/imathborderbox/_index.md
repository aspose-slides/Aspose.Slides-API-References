---
title: IMathBorderBox
second_title: Aspose.Slides for Java API 参考
description: 在 IMathElement 周围绘制矩形或其他类型的边框。
type: docs
url: /zh/com.aspose.slides/imathborderbox/
---
**所有实现的接口:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

在 IMathElement 周围绘制矩形或其他类型的边框。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基本参数 |
| [getHideTop()](#getHideTop--) | 隐藏顶部边缘（默认 false）- 指定边框盒顶部边缘的隐藏或显示状态。 |
| [setHideTop(boolean value)](#setHideTop-boolean-) | 隐藏顶部边缘（默认 false）- 指定边框盒顶部边缘的隐藏或显示状态。 |
| [getHideBottom()](#getHideBottom--) | 隐藏底部边缘（默认 false）- 指定边框盒底部边缘的隐藏或显示状态。 |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | 隐藏底部边缘（默认 false）- 指定边框盒底部边缘的隐藏或显示状态。 |
| [getHideLeft()](#getHideLeft--) | 隐藏左侧边缘（默认 false）- 指定边框盒左侧边缘的隐藏或显示状态。 |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | 隐藏左侧边缘（默认 false）- 指定边框盒左侧边缘的隐藏或显示状态。 |
| [getHideRight()](#getHideRight--) | 隐藏右侧边缘（默认 false）- 指定边框盒右侧边缘的隐藏或显示状态。 |
| [setHideRight(boolean value)](#setHideRight-boolean-) | 隐藏右侧边缘（默认 false）- 指定边框盒右侧边缘的隐藏或显示状态。 |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | 水平删除线（默认 false）- 指定水平删除线的隐藏或显示状态。 |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | 水平删除线（默认 false）- 指定水平删除线的隐藏或显示状态。 |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | 垂直删除线（默认 false）- 指定垂直删除线的隐藏或显示状态。 |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | 垂直删除线（默认 false）- 指定垂直删除线的隐藏或显示状态。 |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | 从左下至右上删除线（默认 false）。 |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | 从左下至右上删除线（默认 false）。 |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | 从左上至右下删除线（默认 false）。 |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | 从左上至右下删除线（默认 false）。 |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基本参数

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**返回:**  
[IMathElement](../../com.aspose.slides/imathelement)

### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

隐藏顶部边缘（默认 false）- 指定边框盒顶部边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**返回:** boolean

### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

隐藏顶部边缘（默认 false）- 指定边框盒顶部边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**参数:**  

| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

隐藏底部边缘（默认 false）- 指定边框盒底部边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**返回:** boolean

### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

隐藏底部边缘（默认 false）- 指定边框盒底部边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**参数:**  

| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

隐藏左侧边缘（默认 false）- 指定边框盒左侧边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**返回:** boolean

### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

隐藏左侧边缘（默认 false）- 指定边框盒左侧边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**参数:**  

| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

隐藏右侧边缘（默认 false）- 指定边框盒右侧边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**返回:** boolean

### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

隐藏右侧边缘（默认 false）- 指定边框盒右侧边缘的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**参数:**  

| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

水平删除线（默认 false）- 指定水平删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**返回:** boolean

### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

水平删除线（默认 false）- 指定水平删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**参数:**  

| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

垂直删除线（默认 false）- 指定垂直删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**返回:** boolean

### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

垂直删除线（默认 false）- 指定垂直删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**参数:**  

| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

从左下至右上删除线（默认 false）。指定边框盒从左下角到右上角的对角线删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**返回:** boolean

### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

从左下至右上删除线（默认 false）。指定边框盒从左下角到右上角的对角线删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**参数:**  

| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

从左上至右下删除线（默认 false）。指定边框盒从左上角到右下角的对角线删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**返回:** boolean

### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

从左上至右下删除线（默认 false）。指定边框盒从左上角到右下角的对角线删除线的隐藏或显示状态。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**参数:**  

| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |