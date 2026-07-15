---
title: MathPhantom
second_title: Aspose.Slides for Android Java API 參考
description: 代表一個 phantom 數學物件 ltmphantgt，會影響其子元素的版面配置，即使不一定顯示它。
type: docs
url: /zh-hant/com.aspose.slides/mathphantom/
---
**繼承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有已實作的介面：**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

代表一個 phantom 數學物件 (<m:phant>)，會影響其子元素的版面配置，即使不一定顯示它。phantom 可以在保留寬度、高度或深度以對齊公式或保留空間的同時隱藏其基礎表達式。可見性與幾何行為由屬性如 Show、ZeroWid、ZeroAsc、ZeroDesc 與 Transp 控制。

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // 隱藏內容
>  phantom.setZeroWidth(false);     // 保留寬度
```
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | 使用指定的基礎數學元素初始化 [MathPhantom](../../com.aspose.slides/mathphantom) 類別的新執行個體。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基礎引數 |
| [getShow()](#getShow--) | 取得或設定指示是否顯示基礎元素的值。 |
| [setShow(boolean value)](#setShow-boolean-) | 取得或設定指示是否顯示基礎元素的值。 |
| [getZeroWidth()](#getZeroWidth--) | 取得或設定指示基礎元素寬度是否視為零的值。 |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | 取得或設定指示基礎元素寬度是否視為零的值。 |
| [getZeroAsc()](#getZeroAsc--) | 取得或設定指示基礎元素上升部（基線以上的高度）是否視為零的值。 |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | 取得或設定指示基礎元素上升部（基線以上的高度）是否視為零的值。 |
| [getZeroDesc()](#getZeroDesc--) | 取得或設定指示基礎元素下降部（基線以下的深度）是否視為零的值。 |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | 取得或設定指示基礎元素下降部（基線以下的深度）是否視為零的值。 |
| [getTransp()](#getTransp--) | 取得或設定指示 phantom 是否對基於類別的間距規則透明的值。 |
| [setTransp(boolean value)](#setTransp-boolean-) | 取得或設定指示 phantom 是否對基於類別的間距規則透明的值。 |
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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 其可見性與版面配置將由 phantom 控制的基礎 [IMathElement](../../com.aspose.slides/imathelement)。此元素定義可能被隱藏或顯示的內容，同時仍影響周圍數學式的幾何對齊。 |

--------------------

phantom 元素用於保留或抑制其基礎表達式的視覺空間，而不一定顯示它。它對應於 OMML 元素 <m:phant>。 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

基礎引數

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

取得或設定指示是否顯示基礎元素的值。

--------------------

當為 false 時，基礎元素被隱藏，但根據其他 phantom 設定可能仍佔用空間。對應於 OMML 屬性 m:show。

**傳回值：**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

取得或設定指示是否顯示基礎元素的值。

--------------------

當為 false 時，基礎元素被隱藏，但根據其他 phantom 設定可能仍佔用空間。對應於 OMML 屬性 m:show。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

取得或設定指示基礎元素寬度是否視為零的值。

--------------------

當為 true 時，phantom 不為其基礎保留水平空間。對應於 OMML 屬性 m:zeroWid。

**傳回值：**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

取得或設定指示基礎元素寬度是否視為零的值。

--------------------

當為 true 時，phantom 不為其基礎保留水平空間。對應於 OMML 屬性 m:zeroWid。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

取得或設定指示基礎元素上升部（基線以上的高度）是否視為零的值。

--------------------

當為 true 時，phantom 不提升周圍數學行的基線。對應於 OMML 屬性 m:zeroAsc。

**傳回值：**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

取得或設定指示基礎元素上升部（基線以上的高度）是否視為零的值。

--------------------

當為 true 時，phantom 不提升周圍數學行的基線。對應於 OMML 屬性 m:zeroAsc。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

取得或設定指示基礎元素下降部（基線以下的深度）是否視為零的值。

--------------------

當為 true 時，phantom 不降低周圍數學行的基線。對應於 OMML 屬性 m:zeroDesc。

**傳回值：**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

取得或設定指示基礎元素下降部（基線以下的深度）是否視為零的值。

--------------------

當為 true 時，phantom 不降低周圍數學行的基線。對應於 OMML 屬性 m:zeroDesc。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

取得或設定指示 phantom 是否對基於類別的間距規則透明的值。

--------------------

當為 true 時，phantom 內的運算子與符號仍會影響其周圍的數學間距（如同可見）。當為 false 時，基於類別的間距會被忽略。對應於 OMML 屬性 m:transp。

**傳回值：**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

取得或設定指示 phantom 是否對基於類別的間距規則透明的值。

--------------------

當為 true 時，phantom 內的運算子與符號仍會影響其周圍的數學間距（如同可見）。當為 false 時，基於類別的間距會被忽略。對應於 OMML 屬性 m:transp。

**參數：**
| 參數 | 類型 | 說明 |
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