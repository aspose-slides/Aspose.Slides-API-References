---
title: MathBorderBox
second_title: Aspose.Slides for Android via Java API 參考文件
description: 在 IMathElement 周圍繪製矩形或其他邊框。
type: docs
url: /zh-hant/com.aspose.slides/mathborderbox/
---
**繼承關係：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有實作介面：**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

在 IMathElement 周圍繪製矩形或其他邊框。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## 建構函式

| 建構子 | 說明 |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | 建立具有矩形邊框的 MathBorderBox 元素 |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 建立 MathBorderBox 元素 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getHideTop()](#getHideTop--) | 隱藏頂部邊緣 (預設為 false) - 指定邊框盒頂部邊緣的隱藏或顯示狀態。 |
| [setHideTop(boolean value)](#setHideTop-boolean-) | 隱藏頂部邊緣 (預設為 false) - 指定邊框盒頂部邊緣的隱藏或顯示狀態。 |
| [getHideBottom()](#getHideBottom--) | 隱藏底部邊緣 (預設為 false) - 指定邊框盒底部邊緣的隱藏或顯示狀態。 |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | 隱藏底部邊緣 (預設為 false) - 指定邊框盒底部邊緣的隱藏或顯示狀態。 |
| [getHideLeft()](#getHideLeft--) | 隱藏左側邊緣 (預設為 false) - 指定邊框盒左側邊緣的隱藏或顯示狀態。 |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | 隱藏左側邊緣 (預設為 false) - 指定邊框盒左側邊緣的隱藏或顯示狀態。 |
| [getHideRight()](#getHideRight--) | 隱藏右側邊緣 (預設為 false) - 指定邊框盒右側邊緣的隱藏或顯示狀態。 |
| [setHideRight(boolean value)](#setHideRight-boolean-) | 隱藏右側邊緣 (預設為 false) - 指定邊框盒右側邊緣的隱藏或顯示狀態。 |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | 刪除線水平 (預設為 false) - 指定水平刪除線的隱藏或顯示狀態。 |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | 刪除線水平 (預設為 false) - 指定水平刪除線的隱藏或顯示狀態。 |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | 刪除線垂直 (預設為 false) - 指定垂直刪除線的隱藏或顯示狀態。 |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | 刪除線垂直 (預設為 false) - 指定垂直刪除線的隱藏或顯示狀態。 |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | 從左下至右上刪除線 (預設為 false)。 |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | 從左下至右上刪除線 (預設為 false)。 |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | 從左上至右下刪除線 (預設為 false)。 |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | 從左上至右下刪除線 (預設為 false)。 |
| [getChildren()](#getChildren--) | 取得子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) |  

### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

建立具有矩形邊框的 MathBorderBox 元素

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用於邊框盒的基礎元素。可以為 null。 |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

建立 MathBorderBox 元素

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用於邊框盒的基礎元素 |
| hideTop | boolean | 隱藏頂部邊緣 |
| hideBottom | boolean | 隱藏底部邊緣 |
| hideLeft | boolean | 隱藏左側邊緣 |
| hideRight | boolean | 隱藏右側邊緣 |
| strikethroughHorizontal | boolean | 刪除線水平 |
| strikethroughVertical | boolean | 刪除線垂直 |
| strikethroughBottomLeftToTopRight | boolean | 從左下至右上刪除線 |
| strikethroughTopLeftToBottomRight | boolean | 從左上至右下刪除線 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

基礎參數

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

隱藏頂部邊緣 (預設為 false) - 指定邊框盒頂部邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**返回：**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

隱藏頂部邊緣 (預設為 false) - 指定邊框盒頂部邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

隱藏底部邊緣 (預設為 false) - 指定邊框盒底部邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**返回：**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

隱藏底部邊緣 (預設為 false) - 指定邊框盒底部邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

隱藏左側邊緣 (預設為 false) - 指定邊框盒左側邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**返回：**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

隱藏左側邊緣 (預設為 false) - 指定邊框盒左側邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

隱藏右側邊緣 (預設為 false) - 指定邊框盒右側邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**返回：**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

隱藏右側邊緣 (預設為 false) - 指定邊框盒右側邊緣的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

刪除線水平 (預設為 false) - 指定水平刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**返回：**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

刪除線水平 (預設為 false) - 指定水平刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

刪除線垂直 (預設為 false) - 指定垂直刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**返回：**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

刪除線垂直 (預設為 false) - 指定垂直刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

從左下至右上刪除線 (預設為 false)。指定從左下角到右上角的對角刪除線的隱藏或顯示狀態。

--------------------

> ```
public final boolean getStrikethroughBottomLeftToTopRight()
```

**返回：**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

從左下至右上刪除線 (預設為 false)。指定從左下角到右上角的對角刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

從左上至右下刪除線 (預設為 false)。指定從左上角到右下角的對角刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**返回：**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

從左上至右下刪除線 (預設為 false)。指定從左上角到右下角的對角刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

取得子元素

**返回：**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

控制字元屬性

**返回：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps