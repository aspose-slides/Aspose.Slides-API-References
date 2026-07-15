---
title: IMathBorderBox
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 在 IMathElement 周圍繪製矩形或其他形狀的邊框。
type: docs
url: /zh-hant/com.aspose.slides/imathborderbox/
---
**所有已實作的介面:**
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

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getHideTop()](#getHideTop--) | 隱藏上邊緣（預設為 false） - 指定邊框盒的上邊緣的隱藏或顯示狀態。 |
| [setHideTop(boolean value)](#setHideTop-boolean-) | 隱藏上邊緣（預設為 false） - 指定邊框盒的上邊緣的隱藏或顯示狀態。 |
| [getHideBottom()](#getHideBottom--) | 隱藏下邊緣（預設為 false） - 指定邊框盒的下邊緣的隱藏或顯示狀態。 |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | 隱藏下邊緣（預設為 false） - 指定邊框盒的下邊緣的隱藏或顯示狀態。 |
| [getHideLeft()](#getHideLeft--) | 隱藏左邊緣（預設為 false） - 指定邊框盒的左邊緣的隱藏或顯示狀態。 |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | 隱藏左邊緣（預設為 false） - 指定邊框盒的左邊緣的隱藏或顯示狀態。 |
| [getHideRight()](#getHideRight--) | 隱藏右邊緣（預設為 false） - 指定邊框盒的右邊緣的隱藏或顯示狀態。 |
| [setHideRight(boolean value)](#setHideRight-boolean-) | 隱藏右邊緣（預設為 false） - 指定邊框盒的右邊緣的隱藏或顯示狀態。 |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | 水平刪除線（預設為 false） - 指定水平刪除線的隱藏或顯示狀態。 |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | 水平刪除線（預設為 false） - 指定水平刪除線的隱藏或顯示狀態。 |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | 垂直刪除線（預設為 false） - 指定垂直刪除線的隱藏或顯示狀態。 |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | 垂直刪除線（預設為 false） - 指定垂直刪除線的隱藏或顯示狀態。 |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | 從左下到右上刪除線（預設為 false）。 |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | 從左下到右上刪除線（預設為 false）。 |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | 從左上到右下刪除線（預設為 false）。 |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | 從左上到右下刪除線（預設為 false）。 |

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

**返回:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

隱藏上邊緣（預設為 false） - 指定邊框盒的上邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**返回:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

隱藏上邊緣（預設為 false） - 指定邊框盒的上邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

隱藏下邊緣（預設為 false） - 指定邊框盒的下邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**返回:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

隱藏下邊緣（預設為 false） - 指定邊框盒的下邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

隱藏左邊緣（預設為 false） - 指定邊框盒的左邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**返回:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

隱藏左邊緣（預設為 false） - 指定邊框盒的左邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

隱藏右邊緣（預設為 false） - 指定邊框盒的右邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**返回:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

隱藏右邊緣（預設為 false） - 指定邊框盒的右邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

水平刪除線（預設為 false） - 指定水平刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**返回:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

水平刪除線（預設為 false） - 指定水平刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

垂直刪除線（預設為 false） - 指定垂直刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**返回:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

垂直刪除線（預設為 false） - 指定垂直刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

從左下到右上刪除線（預設為 false）。指定邊框盒左下角到右上角的對角刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**返回:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

從左下到右上刪除線（預設為 false）。指定邊框盒左下角到右上角的對角刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

從左上到右下刪除線（預設為 false）。指定邊框盒左上角到右下角的對角刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**返回:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

從左上到右下刪除線（預設為 false）。指定邊框盒左上角到右下角的對角刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |