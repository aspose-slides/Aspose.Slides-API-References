---
title: IMathRadical
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 基底と任意の次数からなる根関数を指定します。
type: docs
url: /ja/com.aspose.slides/imathradical/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

基底と任意の次数からなる根関数を指定します。根オブジェクトの例は \\u221a\\ud835\\udc65 です。

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | 基底引数 |
| [getDegree()](#getDegree--) | 次数引数 |
| [getHideDegree()](#getHideDegree--) | Hide degree When が true の場合、次数は表示されません（例: \\u221a\\ud835\\udc65） |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree When が true の場合、次数は表示されません（例: \\u221a\\ud835\\udc65） |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


基底引数

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
>  IMathElement baseElem = radical.getBase();
>  ```


**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


次数引数

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  IMathElement degreeElem = radical.getDegree();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Hide degree When が true の場合、次数は表示されません（例: \\u221a\\ud835\\udc65）

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  radical.setHideDegree(true);
> ```

**戻り値:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Hide degree When が true の場合、次数は表示されません（例: \\u221a\\ud835\\udc65）

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // cube root
>  radical.setHideDegree(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |