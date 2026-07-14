---
title: IMathRadical
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 기본과 선택적 차수로 구성된 급수 함수를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathradical/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

기본과 선택적 차수로 구성된 급수 함수를 지정합니다. 급수 객체의 예는 \\u221a\\ud835\\udc65입니다.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 세제곱근
>  ```

## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base 인수 |
| [getDegree()](#getDegree--) | Degree 인수 |
| [getHideDegree()](#getHideDegree--) | Hide degree가 true인 경우, 차수는 표시되지 않으며, \\u221a\\ud835\\udc65와 같이 표시됩니다. |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree가 true인 경우, 차수는 표시되지 않으며, \\u221a\\ud835\\udc65와 같이 표시됩니다. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Base 인수

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 세제곱근
>  IMathElement baseElem = radical.getBase();
>  ```


**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```


Degree 인수

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 세제곱근
>  IMathElement degreeElem = radical.getDegree();
>  ```


**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```


Hide degree가 true인 경우, 차수는 표시되지 않으며, \\u221a\\ud835\\udc65와 같이 표시됩니다.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 세제곱근
>  radical.setHideDegree(true);
>  ```


**Returns:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```


Hide degree가 true인 경우, 차수는 표시되지 않으며, \\u221a\\ud835\\udc65와 같이 표시됩니다.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 세제곱근
>  radical.setHideDegree(true);
>  ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |