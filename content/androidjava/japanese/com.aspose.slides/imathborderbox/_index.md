---
title: IMathBorderBox
second_title: Java API リファレンスを介した Aspose.Slides for Android
description: IMathElement の周りに長方形またはその他の枠線を描画します。
type: docs
url: /ja/com.aspose.slides/imathborderbox/
---
**すべての実装インターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

IMathElement の周りに長方形またはその他の枠線を描画します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | 基本引数 |
| [getHideTop()](#getHideTop--) | 上端の非表示 (デフォルトは false) - ボーダー ボックスの上端が非表示か表示かの状態を指定します。 |
| [setHideTop(boolean value)](#setHideTop-boolean-) | 上端の非表示 (デフォルトは false) - ボーダー ボックスの上端が非表示か表示かの状態を指定します。 |
| [getHideBottom()](#getHideBottom--) | 下端の非表示 (デフォルトは false) - ボーダー ボックスの下端が非表示か表示かの状態を指定します。 |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | 下端の非表示 (デフォルトは false) - ボーダー ボックスの下端が非表示か表示かの状態を指定します。 |
| [getHideLeft()](#getHideLeft--) | 左端の非表示 (デフォルトは false) - ボーダー ボックスの左端が非表示か表示かの状態を指定します。 |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | 左端の非表示 (デフォルトは false) - ボーダー ボックスの左端が非表示か表示かの状態を指定します。 |
| [getHideRight()](#getHideRight--) | 右端の非表示 (デフォルトは false) - ボーダー ボックスの右端が非表示か表示かの状態を指定します。 |
| [setHideRight(boolean value)](#setHideRight-boolean-) | 右端の非表示 (デフォルトは false) - ボーダー ボックスの右端が非表示か表示かの状態を指定します。 |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | 水平取り消し線 (デフォルトは false) - 水平取り消し線の非表示または表示状態を指定します。 |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | 水平取り消し線 (デフォルトは false) - 水平取り消し線の非表示または表示状態を指定します。 |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | 垂直取り消し線 (デフォルトは false) - 垂直取り消し線の非表示または表示状態を指定します。 |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | 垂直取り消し線 (デフォルトは false) - 垂直取り消し線の非表示または表示状態を指定します。 |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | 左下から右上への取り消し線 (デフォルトは false)。左下角から右上角への対角線の非表示または表示状態を指定します。 |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | 左下から右上への取り消し線 (デフォルトは false)。左下角から右上角への対角線の非表示または表示状態を指定します。 |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | 左上から右下への取り消し線 (デフォルトは false)。左上角から右下角への対角線の非表示または表示状態を指定します。 |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | 左上から右下への取り消し線 (デフォルトは false)。左上角から右下角への対角線の非表示または表示状態を指定します。 |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基本引数

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

上端の非表示 (デフォルトは false) - ボーダー ボックスの上端が非表示か表示かの状態を指定します。

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

上端の非表示 (デフォルトは false) - ボーダー ボックスの上端が非表示か表示かの状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

下端の非表示 (デフォルトは false) - ボーダー ボックスの下端が非表示か表示かの状態を指定します。

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

下端の非表示 (デフォルトは false) - ボーダー ボックスの下端が非表示か表示かの状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

左端の非表示 (デフォルトは false) - ボーダー ボックスの左端が非表示か表示かの状態を指定します。

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

左端の非表示 (デフォルトは false) - ボーダー ボックスの左端が非表示か表示かの状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

右端の非表示 (デフォルトは false) - ボーダー ボックスの右端が非表示か表示かの状態を指定します。

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

右端の非表示 (デフォルトは false) - ボーダー ボックスの右端が非表示か表示かの状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

水平取り消し線 (デフォルトは false) - 水平取り消し線の非表示または表示状態を指定します。

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

水平取り消し線 (デフォルトは false) - 水平取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

垂直取り消し線 (デフォルトは false) - 垂直取り消し線の非表示または表示状態を指定します。

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

垂直取り消し線 (デフォルトは false) - 垂直取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

左下から右上への取り消し線 (デフォルトは false)。左下角から右上角への対角線の非表示または表示状態を指定します。

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

左下から右上への取り消し線 (デフォルトは false)。左下角から右上角への対角線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

左上から右下への取り消し線 (デフォルトは false)。左上角から右下角への対角線の非表示または表示状態を指定します。

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

左上から右下への取り消し線 (デフォルトは false)。左上角から右下角への対角線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |