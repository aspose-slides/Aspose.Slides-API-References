---
title: IMathBorderBox
second_title: Aspose.Slides Java API 參考
description: 在 IMathElement 周圍繪製矩形或其他形狀的邊框。
type: docs
url: /zh-hant/com.aspose.slides/imathborderbox/
---
**已實作的介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

在 IMathElement 周圍繪製矩形或其他形狀的邊框。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getHideTop()](#getHideTop--) | 隱藏上邊緣（default is false） - specifies the hidden or shown state of the top edge of border box. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | 隱藏上邊緣（default is false） - specifies the hidden or shown state of the top edge of border box. |
| [getHideBottom()](#getHideBottom--) | 隱藏下邊緣（default is false） - specifies the hidden or shown state of the bottom edge of border box. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | 隱藏下邊緣（default is false） - specifies the hidden or shown state of the bottom edge of border box. |
| [getHideLeft()](#getHideLeft--) | 隱藏左邊緣（default is false） - specifies the hidden or shown state of the left edge of border box. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | 隱藏左邊緣（default is false） - specifies the hidden or shown state of the left edge of border box. |
| [getHideRight()](#getHideRight--) | 隱藏右邊緣（default is false） - specifies the hidden or shown state of the right edge of border box. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | 隱藏右邊緣（default is false） - specifies the hidden or shown state of the right edge of border box. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | 水平刪除線（default is false） - specifies the hidden or shown state of a strikethrough horizontal line. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | 水平刪除線（default is false） - specifies the hidden or shown state of a strikethrough horizontal line. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | 垂直刪除線（default is false） - specifies the hidden or shown state of a strikethrough vertical line. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | 垂直刪除線（default is false） - specifies the hidden or shown state of a strikethrough vertical line. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Strikethrough Top-Left to Bottom-Right (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Strikethrough Top-Left to Bottom-Right (default is false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基礎參數

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```


**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

隱藏上邊緣（default is false） - specifies the hidden or shown state of the top edge of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**返回值：**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

隱藏上邊緣（default is false） - specifies the hidden or shown state of the top edge of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

隱藏下邊緣（default is false） - specifies the hidden or shown state of the bottom edge of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**返回值：**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

隱藏下邊緣（default is false） - specifies the hidden or shown state of the bottom edge of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

隱藏左邊緣（default is false） - specifies the hidden or shown state of the left edge of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**返回值：**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

隱藏左邊緣（default is false） - specifies the hidden or shown state of the left edge of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

隱藏右邊緣（default is false） - specifies the hidden or shown state of the right edge of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**返回值：**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

隱藏右邊緣（default is false） - specifies the hidden or shown state of the right edge of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

水平刪除線（default is false） - specifies the hidden or shown state of a strikethrough horizontal line.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**返回值：**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

水平刪除線（default is false） - specifies the hidden or shown state of a strikethrough horizontal line.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

垂直刪除線（default is false） - specifies the hidden or shown state of a strikethrough vertical line.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**返回值：**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

垂直刪除線（default is false） - specifies the hidden or shown state of a strikethrough vertical line.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

Strikethrough Bottom-Left to Top-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the bottom-left corner to the top-right corner of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**返回值：**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

Strikethrough Bottom-Left to Top-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the bottom-left corner to the top-right corner of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

Strikethrough Top-Left to Bottom-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the top-left corner to the bottom-right corner of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**返回值：**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

Strikethrough Top-Left to Bottom-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the top-left corner to the bottom-right corner of border box.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |