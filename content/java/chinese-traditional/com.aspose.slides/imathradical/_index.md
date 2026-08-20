---
title: IMathRadical
second_title: Aspose.Slides for Java API 參考文件
description: 指定根號函式，由基底和可選的指數組成。
type: docs
url: /zh-hant/com.aspose.slides/imathradical/
---
**所有已實作的介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

指定根號函式，由基底和可選的指數組成。根號物件的範例為 \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
```
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基底參數 |
| [getDegree()](#getDegree--) | 指數參數 |
| [getHideDegree()](#getHideDegree--) | 當 Hide degree 為 true 時，degree 不會顯示，如 \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | 當 Hide degree 為 true 時，degree 不會顯示，如 \\u221a\\ud835\\udc65 |
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

**返回：**
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


**返回：**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


當 Hide degree 為 true 時，degree 不會顯示，如 \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
>  radical.setHideDegree(true);
>  ```


**返回：**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


當 Hide degree 為 true 時，degree 不會顯示，如 \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
>  radical.setHideDegree(true);
>  ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |