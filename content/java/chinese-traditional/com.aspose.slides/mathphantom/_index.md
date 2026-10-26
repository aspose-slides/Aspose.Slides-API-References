---
title: MathPhantom
second_title: Aspose.Slides Java API 參考
description: 表示一個幽靈數學物件 ltmphantgt，會影響其子元素的版面配置，但不一定顯示它。
type: docs
url: /zh-hant/com.aspose.slides/mathphantom/
---
**繼承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**全部已實作的介面：**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

表示一個幽靈數學物件 (<m:phant>)，它會影響子元素的版面配置，但不一定顯示出來。幽靈可以隱藏其基礎表達式，同時保留寬度、高度或深度，以對齊公式或保留空間。可見性與幾何行為由屬性如 Show、ZeroWid、ZeroAsc、ZeroDesc 和 Transp 控制。

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // 隱藏內容
>  phantom.setZeroWidth(false);     // 保持寬度
```
## 建構函式

| 建構子 | 描述 |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | 使用指定的基礎數學元素初始化 [MathPhantom](../../com.aspose.slides/mathphantom) 類別的新執行個體。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getShow()](#getShow--) | 取得或設定一個值，以指示是否顯示基礎元素。 |
| [setShow(boolean value)](#setShow-boolean-) | 取得或設定一個值，以指示是否顯示基礎元素。 |
| [getZeroWidth()](#getZeroWidth--) | 取得或設定一個值，以指示是否將基礎元素的寬度視為零。 |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | 取得或設定一個值，以指示是否將基礎元素的寬度視為零。 |
| [getZeroAsc()](#getZeroAsc--) | 取得或設定一個值，以指示是否將基礎元素的上升高度（基線以上的高度）視為零。 |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | 取得或設定一個值，以指示是否將基礎元素的上升高度（基線以上的高度）視為零。 |
| [getZeroDesc()](#getZeroDesc--) | 取得或設定一個值，以指示是否將基礎元素的下降深度（基線以下的深度）視為零。 |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | 取得或設定一個值，以指示是否將基礎元素的下降深度（基線以下的深度）視為零。 |
| [getTransp()](#getTransp--) | 取得或設定一個值，以指示幽靈在基於類別的間距規則下是否為透明。 |
| [setTransp(boolean value)](#setTransp-boolean-) | 取得或設定一個值，以指示幽靈在基於類別的間距規則下是否為透明。 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字元屬性 |
| [getChildren()](#getChildren--) | 取得子元素 |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

使用指定的基礎數學元素初始化 [MathPhantom](../../com.aspose.slides/mathphantom) 類別的新執行個體。

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 此基礎 [IMathElement](../../com.aspose.slides/imathelement) 的可見性和版面配置將由幽靈控制。此元素定義可能被隱藏或顯示的內容，同時仍會影響周圍數學公式的幾何對齊。 |

幽靈元素用於保留或抑制其基礎表達式的視覺空間，而不一定顯示出來。它對應於 OMML 元素 <m:phant>。

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

基礎參數

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**傳回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

取得或設定一個值，以指示是否顯示基礎元素。

當為 false 時，基礎元素被隱藏，但根據其他幽靈設定，仍可能佔用空間。對應於 OMML 屬性 m:show。

**傳回值：**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

取得或設定一個值，以指示是否顯示基礎元素。

當為 false 時，基礎元素被隱藏，但根據其他幽靈設定，仍可能佔用空間。對應於 OMML 屬性 m:show。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

取得或設定一個值，以指示是否將基礎元素的寬度視為零。

當為 true 時，幽靈不為其基礎保留水平空間。對應於 OMML 屬性 m:zeroWid。

**傳回值：**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

取得或設定一個值，以指示是否將基礎元素的寬度視為零。

當為 true 時，幽靈不為其基礎保留水平空間。對應於 OMML 屬性 m:zeroWid。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

取得或設定一個值，以指示是否將基礎元素的上升高度（基線以上的高度）視為零。

當為 true 時，幽靈不會提升周圍數學行的基線。對應於 OMML 屬性 m:zeroAsc。

**傳回值：**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

取得或設定一個值，以指示是否將基礎元素的上升高度（基線以上的高度）視為零。

當為 true 時，幽靈不會提升周圍數學行的基線。對應於 OMML 屬性 m:zeroAsc。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

取得或設定一個值，以指示是否將基礎元素的下降深度（基線以下的深度）視為零。

當為 true 時，幽靈不會降低周圍數學行的基線。對應於 OMML 屬性 m:zeroDesc。

**傳回值：**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

取得或設定一個值，以指示是否將基礎元素的下降深度（基線以下的深度）視為零。

當為 true 時，幽靈不會降低周圍數學行的基線。對應於 OMML 屬性 m:zeroDesc。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

取得或設定一個值，以指示幽靈在基於類別的間距規則下是否為透明。

當為 true 時，幽靈內的運算子和符號仍會影響幽靈周圍的數學間距（如同可見）。當為 false 時，類別基礎的間距會被忽略。對應於 OMML 屬性 m:transp。

**傳回值：**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

取得或設定一個值，以指示幽靈在基於類別的間距規則下是否為透明。

當為 true 時，幽靈內的運算子和符號仍會影響幽靈周圍的數學間距（如同可見）。當為 false 時，類別基礎的間距會被忽略。對應於 OMML 屬性 m:transp。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

控制字元屬性

**傳回值：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

取得子元素

**傳回值：**
com.aspose.slides.IMathElement[]