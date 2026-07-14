---
title: IMathRightSubSuperscriptElement
second_title: Android용 Aspose.Slides Java API 레퍼런스
description: base와 base 오른쪽에 배치된 subscript와 superscript으로 구성된 Sub-Superscript 객체를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathrightsubsuperscriptelement/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

Sub-Superscript 객체는 base와 base 오른쪽에 배치된 subscript와 superscript으로 구성됩니다.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | Base 인수 |
| [getSubscript()](#getSubscript--) | Subscript 인수 |
| [getSuperscript()](#getSuperscript--) | Superscript 인수 |
| [getAlignScripts()](#getAlignScripts--) | subscript/superscript의 정렬을 지정합니다. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | subscript/superscript의 정렬을 지정합니다. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Base 인수

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Subscript 인수

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Superscript 인수

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```

subscript/superscript의 정렬을 지정합니다. true이면 subscript와 superscript이 서로 수평으로 정렬됩니다. false이면 base의 형태에 맞게 커닝됩니다. 기본값은 false입니다.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**반환값:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```

subscript/superscript의 정렬을 지정합니다. true이면 subscript와 superscript이 서로 수평으로 정렬됩니다. false이면 base의 형태에 맞게 커닝됩니다. 기본값은 false입니다.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |