---
title: IMathFunction
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 인수에 대한 함수를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathfunction/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

인수의 함수를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getName()](#getName--) | 함수 이름 예를 들어, 함수 이름은 sin 및 cos입니다. |
| [getBase()](#getBase--) | 함수 인수 |
### getName() {#getName--}
```
public abstract IMathElement getName()
```


함수 이름 예를 들어, 함수 이름은 sin 및 cos입니다.

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**반환:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


함수 인수

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**반환:**
[IMathElement](../../com.aspose.slides/imathelement)