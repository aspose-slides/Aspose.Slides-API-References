---
title: IMathRadical
second_title: Aspose.Slides for Java API 参考
description: 指定由基数和可选指数组成的根函数。
type: docs
url: /zh/com.aspose.slides/imathradical/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

指定根函数，包括基数和可选的指数。例如，根对象是 \\u221a\\ud835\\udc65。

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
>  ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getDegree()](#getDegree--) | Degree argument |
| [getHideDegree()](#getHideDegree--) | Hide degree When 为 true 时，度数不显示，如 \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree When 为 true 时，度数不显示，如 \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


基数参数

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
>  IMathElement baseElem = radical.getBase();
>  ```


**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


指数参数

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
>  IMathElement degreeElem = radical.getDegree();
>  ```

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Hide degree 为 true 时，度数不显示，如 \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
>  radical.setHideDegree(true);
>  ```

**返回值：**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Hide degree 为 true 时，度数不显示，如 \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 立方根
>  radical.setHideDegree(true);
>  ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |