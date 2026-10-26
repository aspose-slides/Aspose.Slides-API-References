---
title: IMathPhantom
second_title: Aspose.Slides 的 Java API 參考
description: 表示一個幻影數學物件 ltmphantgt，會影響其子元素的版面配置，但不一定顯示它。
type: docs
url: /zh-hant/com.aspose.slides/imathphantom/
---
**所有已實作的介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

表示一個幻影數學物件 (<m:phant>)，它會影響子元素的版面配置，但不一定顯示該元素。幻影可以隱藏其基礎表達式，同時保留其寬度、高度或深度，以對齊公式或保留空間。可見性和幾何行為由屬性如 Show、ZeroWid、ZeroAsc、ZeroDesc 和 Transp 控制。

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // 隱藏內容
>  phantom.setZeroWidth(false);     // 保留寬度
>  ```

## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getShow()](#getShow--) | 取得或設定一個值，指示是否顯示基礎元素。 |
| [setShow(boolean value)](#setShow-boolean-) | 取得或設定一個值，指示是否顯示基礎元素。 |
| [getZeroWidth()](#getZeroWidth--) | 取得或設定一個值，指示是否將基礎元素的寬度視為零。 |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | 取得或設定一個值，指示是否將基礎元素的寬度視為零。 |
| [getZeroAsc()](#getZeroAsc--) | 取得或設定一個值，指示是否將基礎元素的上升（基線上方的高度）視為零。 |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | 取得或設定一個值，指示是否將基礎元素的上升（基線上方的高度）視為零。 |
| [getZeroDesc()](#getZeroDesc--) | 取得或設定一個值，指示是否將基礎元素的下降（基線下方的深度）視為零。 |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | 取得或設定一個值，指示是否將基礎元素的下降（基線下方的深度）視為零。 |
| [getTransp()](#getTransp--) | 取得或設定一個值，指示幻影在基於類別的間距規則下是否透明。 |
| [setTransp(boolean value)](#setTransp-boolean-) | 取得或設定一個值，指示幻影在基於類別的間距規則下是否透明。 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基礎參數

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**傳回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

取得或設定一個值，指示是否顯示基礎元素。

--------------------

當為 false 時，基礎元素會被隱藏，但可能仍會佔用空間，取決於其他 phantom 設定。對應 OMML 屬性 m:show。

**傳回值：**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

取得或設定一個值，指示是否顯示基礎元素。

--------------------

當為 false 時，基礎元素會被隱藏，但可能仍會佔用空間，取決於其他 phantom 設定。對應 OMML 屬性 m:show。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

取得或設定一個值，指示是否將基礎元素的寬度視為零。

--------------------

當為 true 時，幻影不會為其基礎元素保留水平空間。對應 OMML 屬性 m:zeroWid。

**傳回值：**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

取得或設定一個值，指示是否將基礎元素的寬度視為零。

--------------------

當為 true 時，幻影不會為其基礎元素保留水平空間。對應 OMML 屬性 m:zeroWid。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

取得或設定一個值，指示是否將基礎元素的上升（基線上方的高度）視為零。

--------------------

當為 true 時，幻影不會提升周圍數學行的基線。對應 OMML 屬性 m:zeroAsc。

**傳回值：**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

取得或設定一個值，指示是否將基礎元素的上升（基線上方的高度）視為零。

--------------------

當為 true 時，幻影不會提升周圍數學行的基線。對應 OMML 屬性 m:zeroAsc。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

取得或設定一個值，指示是否將基礎元素的下降（基線下方的深度）視為零。

--------------------

當為 true 時，幻影不會降低周圍數學行的基線。對應 OMML 屬性 m:zeroDesc。

**傳回值：**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

取得或設定一個值，指示是否將基礎元素的下降（基線下方的深度）視為零。

--------------------

當為 true 時，幻影不會降低周圍數學行的基線。對應 OMML 屬性 m:zeroDesc。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

取得或設定一個值，指示幻影在基於類別的間距規則下是否透明。

--------------------

當為 true 時，幻影內的運算子和符號仍會影響幻影周圍的數學間距（如同可見）。當為 false 時，基於類別的間距將被忽略。對應 OMML 屬性 m:transp。

**傳回值：**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

取得或設定一個值，指示幻影在基於類別的間距規則下是否透明。

--------------------

當為 true 時，幻影內的運算子和符號仍會影響幻影周圍的數學間距（如同可見）。當為 false 時，基於類別的間距將被忽略。對應 OMML 屬性 m:transp。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |