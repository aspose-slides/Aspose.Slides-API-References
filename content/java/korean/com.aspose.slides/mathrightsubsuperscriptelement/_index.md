---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides for Java API 참조
description: 베이스와 베이스 오른쪽에 배치된 아래첨자와 위첨자를 포함하는 Sub-Superscript 객체를 지정합니다.
type: docs
url: /ko/com.aspose.slides/mathrightsubsuperscriptelement/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**All Implemented Interfaces:**  
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)  
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Base와 오른쪽에 배치된 아래첨자와 위첨자를 포함하는 Sub-Superscript 객체를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathRightSubSuperscriptElement 클래스를 새로운 인스턴스로 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSubscript()](#getSubscript--) | 아래첨자 인수 |
| [getSuperscript()](#getSuperscript--) | 위첨자 인수 |
| [getAlignScripts()](#getAlignScripts--) | 아래첨자/위첨자의 정렬을 지정합니다. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | 아래첨자/위첨자의 정렬을 지정합니다. |
| [getChildren()](#getChildren--) | 하위 요소를 가져옵니다 |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```

MathRightSubSuperscriptElement 클래스를 새로운 인스턴스로 초기화합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

아래첨자 인수

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
public final IMathElement getSuperscript()
```

위첨자 인수

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
public final boolean getAlignScripts()
```

아래첨자/위첨자의 정렬을 지정합니다. true이면 아래첨자와 위첨자가 서로 수평으로 정렬됩니다. false이면 기반의 모양에 맞게 커닝됩니다. 기본값은 false입니다.

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
public final void setAlignScripts(boolean value)
```

아래첨자/위첨자의 정렬을 지정합니다. true이면 아래첨자와 위첨자가 서로 수평으로 정렬됩니다. false이면 기반의 모양에 맞게 커닝됩니다. 기본값은 false입니다.

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

하위 요소를 가져옵니다

**반환값:**  
com.aspose.slides.IMathElement[]