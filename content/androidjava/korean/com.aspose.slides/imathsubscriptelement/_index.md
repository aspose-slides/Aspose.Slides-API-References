---
title: IMathSubscriptElement
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 기본과 오른쪽 아래에 배치된 축소된 크기의 아래첨자로 구성된 아래첨자 개체를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathsubscriptelement/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

아래첨자 개체를 지정합니다. 이 개체는 기본과 오른쪽 아래에 배치된 축소된 크기의 아래첨자로 구성됩니다.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getSubscript()](#getSubscript--) | 아래첨자 |
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

아래첨자

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)