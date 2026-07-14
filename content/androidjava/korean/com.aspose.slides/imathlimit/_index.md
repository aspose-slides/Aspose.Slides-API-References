---
title: IMathLimit
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 기준선에 있는 텍스트와 바로 위 또는 아래에 위치한 축소된 텍스트로 구성된 Limit 객체를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathlimit/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

제한 객체를 지정합니다. 이 객체는 기준선에 있는 텍스트와 그 바로 위 또는 아래에 위치한 축소된 텍스트로 구성됩니다.

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getLimit()](#getLimit--) | 제한 인수 |
| [getUpperLimit()](#getUpperLimit--) | 상한 또는 하한을 지정합니다 |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | 상한 또는 하한을 지정합니다 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


기본 인수

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```


제한 인수

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public abstract boolean getUpperLimit()
```


상한 또는 하한을 지정합니다

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**반환값:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public abstract void setUpperLimit(boolean value)
```


상한 또는 하한을 지정합니다

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |