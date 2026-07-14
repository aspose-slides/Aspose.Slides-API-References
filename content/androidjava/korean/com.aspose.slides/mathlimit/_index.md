---
title: MathLimit
second_title: Aspose.Slides for Android용 Java API 참조
description: 기준선 위의 텍스트와 그 바로 위 또는 아래에 있는 축소된 텍스트로 구성된 Limit 객체를 지정합니다.
type: docs
url: /ko/com.aspose.slides/mathlimit/
---
**상속:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**구현된 모든 인터페이스:**
[com.aspose.slides.IMathLimit](../../com.aspose.slides/imathlimit), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathLimit extends MathElementBase implements IMathLimit, IHasControlCharacterProperties
```

기준선 위의 텍스트와 그 바로 위 또는 아래에 있는 축소된 텍스트로 구성된 Limit 객체를 지정합니다.

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | MathLimit 클래스를 새 인스턴스로 초기화합니다. |
| [MathLimit(IMathElement baseArg, IMathElement limit)](#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathLimit 클래스를 하한과 함께 새 인스턴스로 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getLimit()](#getLimit--) | 제한 인수 |
| [getUpperLimit()](#getUpperLimit--) | 상한 또는 하한을 지정합니다. |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | 상한 또는 하한을 지정합니다. |
| [getChildren()](#getChildren--) | 자식 요소를 가져옵니다. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 제어 문자 속성 |
### MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


MathLimit 클래스를 새 인스턴스로 초기화합니다.

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"), false);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| limit | [IMathElement](../../com.aspose.slides/imathelement) |  |
| upperLimit | boolean |  |

### MathLimit(IMathElement baseArg, IMathElement limit) {#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathLimit(IMathElement baseArg, IMathElement limit)
```


MathLimit 클래스를 하한과 함께 새 인스턴스로 초기화합니다.

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| limit | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


기본 인수

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  IMathElement baseArg = limitElement.getBase();
> ```


**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public final IMathElement getLimit()
```


제한 인수

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public final boolean getUpperLimit()
```


상한 또는 하한을 지정합니다.

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  limitElement.setUpperLimit(false);
> ```

**반환값:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public final void setUpperLimit(boolean value)
```


상한 또는 하한을 지정합니다.

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  limitElement.setUpperLimit(false);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


자식 요소를 가져옵니다.

**반환값:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


제어 문자 속성

**반환값:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps