---
title: IMathSuperscriptElement
second_title: Aspose.Slides for Java API 레퍼런스
description: 위에 오른쪽에 배치된 기본과 축소된 크기의 위첨자로 구성된 위첨자 객체를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathsuperscriptelement/
---
**모든 구현된 인터페이스:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

위에 오른쪽에 배치된 기본과 축소된 크기의 위첨자로 구성된 위첨자 객체를 지정합니다

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getSuperscript()](#getSuperscript--) | 위첨자 |
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
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**반환:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

위첨자

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**반환:**  
[IMathElement](../../com.aspose.slides/imathelement)