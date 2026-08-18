---
title: IMathRadical
second_title: Aspose.Slides for Java API リファレンス
description: ベースとオプションの次数からなるラジカル関数を指定します。
type: docs
url: /ja/com.aspose.slides/imathradical/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

ラジカル関数を指定します。ベースとオプションの次数から構成されます。ラジカルオブジェクトの例は \\u221a\\ud835\\udc65 です。

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
```
## メソッド

| Method | 説明 |
| --- | --- |
| [getBase()](#getBase--) | ベース引数 |
| [getDegree()](#getDegree--) | 次数引数 |
| [getHideDegree()](#getHideDegree--) | Hide degree が true のとき、次数は表示されません。例: \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree が true のとき、次数は表示されません。例: \\u221a\\ud835\\udc65 |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

ベース引数

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
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
>  IMathElement degreeElem = radical.getDegree();
>  ```


**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```

Hide degree が true のとき、次数は表示されません。例: \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
>  radical.setHideDegree(true);
> ```


**戻り値:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```

Hide degree が true のとき、次数は表示されません。例: \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
>  radical.setHideDegree(true);
>  ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |