---
title: IMathRadical
second_title: Aspose.Slides for Java API 레퍼런스
description: 베이스와 선택적인 차수로 구성된 루트 함수를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathradical/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

베이스와 선택적인 차수로 구성된 루트 함수를 지정합니다. 루트 객체의 예: \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radial("3"); // 세제곱근
>  ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getDegree()](#getDegree--) | 차수 인수 |
| [getHideDegree()](#getHideDegree--) | `Hide degree When`이 true이면 차수가 표시되지 않으며, 예: \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | `Hide degree When`이 true이면 차수가 표시되지 않으며, 예: \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

기본 인수

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 세제곱근
>  IMathElement baseElem = radical.getBase();
>  ```


**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```

차수 인수

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 세제곱근
>  IMathElement degreeElem = radical.getDegree();
> ```


**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```

`Hide degree When`이 true이면 차수가 표시되지 않으며, 예: \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 세제곱근
>  radical.setHideDegree(true);
>  ```


**반환값:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```

`Hide degree When`이 true이면 차수가 표시되지 않으며, 예: \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // 세제곱근
>  radical.setHideDegree(true);
>  ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |