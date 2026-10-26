---
title: IMathRadical
second_title: Aspose.Slides for Android via Java API 參考文件
description: 指定根號函式，由基底和可選的指數組成。
type: docs
url: /zh-hant/com.aspose.slides/imathradical/
---
**已實作的介面:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

指定根號函式，由基底和可選的指數組成。根號物件的範例為 \\u221a\\ud835\\udc65。

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基底參數 |
| [getDegree()](#getDegree--) | 指數參數 |
| [getHideDegree()](#getHideDegree--) | 隱藏指數。當為 true 時，指數不會顯示，例如 \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | 隱藏指數。當為 true 時，指數不會顯示，例如 \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


基底參數

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
>  IMathElement baseElem = radical.getBase();
>  ```

**傳回值:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


指數參數

--------------------

> ```
> Example:
>  
>  IMMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
>  IMathElement degreeElem = radical.getDegree();
>  ```

**傳回值:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


隱藏指數。當為 true 時，指數不會顯示，例如 \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  radical.setHideDegree(true);
> ```

**傳回值:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


隱藏指數。當為 true 時，指數不會顯示，例如 \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  radical.setHideDegree(true);
> ```

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |