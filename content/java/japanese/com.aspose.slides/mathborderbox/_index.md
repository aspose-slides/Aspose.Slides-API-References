---
title: MathBorderBox
second_title: Aspose.Slides for Java API リファレンス
description: IMathElement の周囲に矩形またはその他の枠線を描画します。
type: docs
url: /ja/com.aspose.slides/mathborderbox/
---
**継承:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

IMathElement の周囲に矩形またはその他の枠線を描画します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | 矩形の枠線で MathBorderBox 要素を作成します |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | MathBorderBox 要素を作成します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | 基本引数 |
| [getHideTop()](#getHideTop--) | 上端を非表示にします（デフォルトは false） - 枠線ボックスの上端の非表示または表示状態を指定します。 |
| [setHideTop(boolean value)](#setHideTop-boolean-) | 上端を非表示にします（デフォルトは false） - 枠線ボックスの上端の非表示または表示状態を指定します。 |
| [getHideBottom()](#getHideBottom--) | 下端を非表示にします（デフォルトは false） - 枠線ボックスの下端の非表示または表示状態を指定します。 |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | 下端を非表示にします（デフォルトは false） - 枠線ボックスの下端の非表示または表示状態を指定します。 |
| [getHideLeft()](#getHideLeft--) | 左端を非表示にします（デフォルトは false） - 枠線ボックスの左端の非表示または表示状態を指定します。 |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | 左端を非表示にします（デフォルトは false） - 枠線ボックスの左端の非表示または表示状態を指定します。 |
| [getHideRight()](#getHideRight--) | 右端を非表示にします（デフォルトは false） - 枠線ボックスの右端の非表示または表示状態を指定します。 |
| [setHideRight(boolean value)](#setHideRight-boolean-) | 右端を非表示にします（デフォルトは false） - 枠線ボックスの右端の非表示または表示状態を指定します。 |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | 水平の取り消し線（デフォルトは false） - 水平取り消し線の非表示または表示状態を指定します。 |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | 水平の取り消し線（デフォルトは false） - 水平取り消し線の非表示または表示状態を指定します。 |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | 垂直の取り消し線（デフォルトは false） - 垂直取り消し線の非表示または表示状態を指定します。 |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | 垂直の取り消し線（デフォルトは false） - 垂直取り消し線の非表示または表示状態を指定します。 |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | 左下から右上への取り消し線（デフォルトは false）。 |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | 左下から右上への取り消し線（デフォルトは false）。 |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | 左上から右下への取り消し線（デフォルトは false）。 |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | 左上から右下への取り消し線（デフォルトは false）。 |
| [getChildren()](#getChildren--) | 子要素を取得します |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 制御文字プロパティ |

### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```


矩形の枠線で MathBorderBox 要素を作成します

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 枠線ボックスが適用される基底要素。null を許容します。 |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


MathBorderBox 要素を作成します

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 枠線ボックスが適用される基底要素 |
| hideTop | boolean | 上端を非表示にする |
| hideBottom | boolean | 下端を非表示にする |
| hideLeft | boolean | 左端を非表示にする |
| hideRight | boolean | 右端を非表示にする |
| strikethroughHorizontal | boolean | 水平の取り消し線 |
| strikethroughVertical | boolean | 垂直の取り消し線 |
| strikethroughBottomLeftToTopRight | boolean | 左下から右上への取り消し線 |
| strikethroughTopLeftToBottomRight | boolean | 左上から右下への取り消し線 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


基本引数

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```


上端を非表示にします（デフォルトは false） - 枠線ボックスの上端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**戻り値:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```


上端を非表示にします（デフォルトは false） - 枠線ボックスの上端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```


下端を非表示にします（デフォルトは false） - 枠線ボックスの下端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**戻り値:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```


下端を非表示にします（デフォルトは false） - 枠線ボックスの下端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```


左端を非表示にします（デフォルトは false） - 枠線ボックスの左端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**戻り値:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```


左端を非表示にします（デフォルトは false） - 枠線ボックスの左端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```


右端を非表示にします（デフォルトは false） - 枠線ボックスの右端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**戻り値:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```


右端を非表示にします（デフォルトは false） - 枠線ボックスの右端の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```


水平の取り消し線（デフォルトは false） - 水平取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**戻り値:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```


水平の取り消し線（デフォルトは false） - 水平取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```


垂直の取り消し線（デフォルトは false） - 垂直取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**戻り値:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```


垂直の取り消し線（デフォルトは false） - 垂直取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```


左下から右上への取り消し線（デフォルトは false）。枠線ボックスの左下隅から右上隅への斜め取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**戻り値:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```


左下から右上への取り消し線（デフォルトは false）。枠線ボックスの左下隅から右上隅への斜め取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```


左上から右下への取り消し線（デフォルトは false）。枠線ボックスの左上隅から右下隅への斜め取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**戻り値:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```


左上から右下への取り消し線（デフォルトは false）。枠線ボックスの左上隅から右下隅への斜め取り消し線の非表示または表示状態を指定します。

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


子要素を取得します

**戻り値:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


制御文字プロパティ

**戻り値:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps