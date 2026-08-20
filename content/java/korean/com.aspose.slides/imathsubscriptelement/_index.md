---
title: IMathSubscriptElement
second_title: Aspose.Slides for Java API 참조
description: 아래와 오른쪽에 배치된 기본과 축소된 크기의 첨자를 포함하는 첨자 객체를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathsubscriptelement/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

아래와 오른쪽에 배치된 기본 및 축소된 크기의 첨자를 포함하는 첨자 객체를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
>  ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getSubscript()](#getSubscript--) | 첨자 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

기본 인수

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

첨자

--------------------

> ```
> 예제:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)