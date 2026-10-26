---
title: MathBorderBox
second_title: Aspose.Slides for Java API 參考
description: 在 IMathElement 周圍繪製矩形或其他類型的邊框。
type: docs
url: /zh-hant/com.aspose.slides/mathborderbox/
---
**繼承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有實作的介面：**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

繪製矩形或其他類型的邊框於 IMathElement 周圍。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## 建構函式

| 建構子 | 說明 |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | 建立帶有矩形邊框的 MathBorderBox 元素 |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 建立 MathBorderBox 元素 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getHideTop()](#getHideTop--) | 隱藏上邊緣（預設為 false）- 指定邊框盒的上邊緣是隱藏還是顯示的狀態。 |
| [setHideTop(boolean value)](#setHideTop-boolean-) | 隱藏上邊緣（預設為 false）- 指定邊框盒的上邊緣是隱藏還是顯示的狀態。 |
| [getHideBottom()](#getHideBottom--) | 隱藏下邊緣（預設為 false）- 指定邊框盒的下邊緣是隱藏還是顯示的狀態。 |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | 隱藏下邊緣（預設為 false）- 指定邊框盒的下邊緣是隱藏還是顯示的狀態。 |
| [getHideLeft()](#getHideLeft--) | 隱藏左邊緣（預設為 false）- 指定邊框盒的左邊緣是隱藏還是顯示的狀態。 |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | 隱藏左邊緣（預設為 false）- 指定邊框盒的左邊緣是隱藏還是顯示的狀態。 |
| [getHideRight()](#getHideRight--) | 隱藏右邊緣（預設為 false）- 指定邊框盒的右邊緣是隱藏還是顯示的狀態。 |
| [setHideRight(boolean value)](#setHideRight-boolean-) | 隱藏右邊緣（預設為 false）- 指定邊框盒的右邊緣是隱藏還是顯示的狀態。 |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | 水平刪除線（預設為 false）- 指定水平刪除線的隱藏或顯示狀態。 |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | 水平刪除線（預設為 false）- 指定水平刪除線的隱藏或顯示狀態。 |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | 垂直刪除線（預設為 false）- 指定垂直刪除線的隱藏或顯示狀態。 |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | 垂直刪除線（預設為 false）- 指定垂直刪除線的隱藏或顯示狀態。 |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | 從左下至右上刪除線（預設為 false）。 |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | 從左下至右上刪除線（預設為 false）。 |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | 從左上至右下刪除線（預設為 false）。 |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | 從左上至右下刪除線（預設為 false）。 |
| [getChildren()](#getChildren--) | 取得子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字元屬性 |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```


建立帶有矩形邊框的 MathBorderBox 元素

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用邊框盒的基礎元素。可以為 null。 |

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用邊框盒的基礎元素 |
| hideTop | boolean | 隱藏上邊緣 |
| hideBottom | boolean | 隱藏下邊緣 |
| hideLeft | boolean | 隱藏左邊緣 |
| hideRight | boolean | 隱藏右邊緣 |
| strikethroughHorizontal | boolean | 水平刪除線 |
| strikethroughVertical | boolean | 垂直刪除線 |
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


**傳回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```


隱藏上邊緣（預設為 false）- 指定邊框盒的上邊緣是隱藏還是顯示的狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**傳回值：**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```


隱藏上邊緣（預設為 false）- 指定邊框盒的上邊緣是隱藏還是顯示的狀態。

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


隱藏下邊緣（預設為 false）- 指定邊框盒的下邊緣是隱藏還是顯示的狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**傳回值：**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```


隱藏下邊緣（預設為 false）- 指定邊框盒的下邊緣是隱藏還是顯示的狀態。

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


隱藏左邊緣（預設為 false）- 指定邊框盒的左邊緣是隱藏還是顯示的狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**傳回值：**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```


隱藏左邊緣（預設為 false）- 指定邊框盒的左邊緣是隱藏還是顯示的狀態。

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


隱藏右邊緣（預設為 false）- 指定邊框盒的右邊緣是隱藏還是顯示的狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**傳回值：**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```


隱藏右邊緣（預設為 false）- 指定邊框盒的右邊緣是隱藏還是顯示的狀態。

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


水平刪除線（預設為 false）- 指定水平刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**傳回值：**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```


水平刪除線（預設為 false）- 指定水平刪除線的隱藏或顯示狀態。

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


垂直刪除線（預設為 false）- 指定垂直刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**傳回值：**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```


垂直刪除線（預設為 false）- 指定垂直刪除線的隱藏或顯示狀態。

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


從左下至右上刪除線（預設為 false）。指定邊框盒左下角至右上角的斜線刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**傳回值：**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```


從左下至右上刪除線（預設為 false）。指定邊框盒左下角至右上角的斜線刪除線的隱藏或顯示狀態。

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


從左上至右下刪除線（預設為 false）。指定邊框盒左上角至右下角的斜線刪除線的隱藏或顯示狀態。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**傳回值：**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```


從左上至右下刪除線（預設為 false）。指定邊框盒左上角至右下角的斜線刪除線的隱藏或顯示狀態。

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

**傳回值：**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


控制字元屬性

**傳回值：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps