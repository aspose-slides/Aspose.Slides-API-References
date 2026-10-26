---
title: IMathBorderBox
second_title: Aspose.Slides for Java API リファレンス
description: IMathElement の周囲に矩形またはその他の枠線を描画します。
type: docs
url: /ja/com.aspose.slides/imathborderbox/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

IMathElement の周囲に矩形またはその他の枠線を描画します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | ベース引数 |
| [getHideTop()](#getHideTop--) | 上端を非表示にする（デフォルトは false） - 境界ボックスの上端の非表示または表示状態を指定します。 |
| [setHideTop(boolean value)](#setHideTop-boolean-) | 上端を非表示にする（デフォルトは false） - 境界ボックスの上端の非表示または表示状態を指定します。 |
| [getHideBottom()](#getHideBottom--) | 下端を非表示にする（デフォルトは false） - 境界ボックスの下端の非表示または表示状態を指定します。 |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | 下端を非表示にする（デフォルトは false） - 境界ボックスの下端の非表示または表示状態を指定します。 |
| [getHideLeft()](#getHideLeft--) | 左端を非表示にする（デフォルトは false） - 境界ボックスの左端の非表示または表示状態を指定します。 |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | 左端を非表示にする（デフォルトは false） - 境界ボックスの左端の非表示または表示状態を指定します。 |
| [getHideRight()](#getHideRight--) | 右端を非表示にする（デフォルトは false） - 境界ボックスの右端の非表示または表示状態を指定します。 |
| [setHideRight(boolean value)](#setHideRight-boolean-) | 右端を非表示にする（デフォルトは false） - 境界ボックスの右端の非表示または表示状態を指定します。 |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | 水平取り消し線（デフォルトは false） - 水平取り消し線の非表示または表示状態を指定します。 |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | 水平取り消し線（デフォルトは false） - 水平取り消し線の非表示または表示状態を指定します。 |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | 垂直取り消し線（デフォルトは false） - 垂直取り消し線の非表示または表示状態を指定します。 |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | 垂直取り消し線（デフォルトは false） - 垂直取り消し線の非表示または表示状態を指定します。 |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | 左下から右上への取り消し線（デフォルトは false）。 |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | 左下から右上への取り消し線（デフォルトは false）。 |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | 左上から右下への取り消し線（デフォルトは false）。 |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | 左上から右下への取り消し線（デフォルトは false）。 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

ベース引数

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

上端を非表示にする（デフォルトは false） - 境界ボックスの上端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**戻り値:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

上端を非表示にする（デフォルトは false） - 境界ボックスの上端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

下端を非表示にする（デフォルトは false） - 境界ボックスの下端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**戻り値:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

下端を非表示にする（デフォルトは false） - 境界ボックスの下端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

左端を非表示にする（デフォルトは false） - 境界ボックスの左端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**戻り値:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

左端を非表示にする（デフォルトは false） - 境界ボックスの左端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

右端を非表示にする（デフォルトは false） - 境界ボックスの右端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**戻り値:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

右端を非表示にする（デフォルトは false） - 境界ボックスの右端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

水平取り消し線（デフォルトは false） - 水平取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**戻り値:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

水平取り消し線（デフォルトは false） - 水平取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

垂直取り消し線（デフォルトは false） - 垂直取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**戻り値:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

垂直取り消し線（デフォルトは false） - 垂直取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

左下から右上への取り消し線（デフォルトは false）。境界ボックスの左下隅から右上隅への対角線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**戻り値:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

左下から右上への取り消し線（デフォルトは false）。境界ボックスの左下隅から右上隅への対角線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

左上から右下への取り消し線（デフォルトは false）。境界ボックスの左上隅から右下隅への対角線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**戻り値:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

左上から右下への取り消し線（デフォルトは false）。境界ボックスの左上隅から右下隅への対角線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |