---
title: MathGroupingCharacter
second_title: Java API를 이용한 Android용 Aspose.Slides 참조
description: 보통 요소 간의 관계를 강조하기 위해 표현식 위 또는 아래에 그룹화 기호를 지정합니다.
type: docs
url: /ko/com.aspose.slides/mathgroupingcharacter/
---
**상속:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**모든 구현된 인터페이스:**  
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

표현식 위나 아래에 그룹화 기호를 지정하여 일반적으로 요소 간의 관계를 강조합니다.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | MathGroupingCharacter 클래스의 새 인스턴스를 기본 그룹화 문자 U+23DF (BOTTOM CURLY BRACKET)로 초기화합니다. |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | MathGroupingCharacter 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBase()](#getBase--) | 기본 인수 |
| [getCharacter()](#getCharacter--) | 그룹화 문자 기본값: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | 그룹화 문자 기본값: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | 그룹화 문자의 위치. |
| [setPosition(int value)](#setPosition-int-) | 그룹화 문자의 위치. |
| [getVerticalJustification()](#getVerticalJustification--) | 그룹 문자에 대한 수직 정렬. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | 그룹 문자에 대한 수직 정렬. |
| [getChildren()](#getChildren--) | 자식 요소 가져오기 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 제어 문자 속성 |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

MathGroupingCharacter 클래스의 새 인스턴스를 기본 그룹화 문자 U+23DF (BOTTOM CURLY BRACKET)로 초기화합니다.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 바가 적용되는 기본 요소 |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

MathGroupingCharacter 클래스의 새 인스턴스를 초기화합니다.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```
**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 바가 적용되는 기본 요소 |
| character | char | 그룹화 문자 |
| position | int | 그룹화 문자의 위치 |
| verticalJustification | int | 그룹 문자에 대한 수직 정렬 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

기본 인수

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```
**반환값:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

그룹화 문자 기본값: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 하단 괄호
> ```
**반환값:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

그룹화 문자 기본값: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 하단 괄호
> ```
**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

그룹화 문자 위치. 기본값: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```
**반환값:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

그룹화 문자 위치. 기본값: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```
**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```

그룹 문자에 대한 수직 정렬. 객체와 기준선 사이의 정렬을 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때, Top 수직 정렬은 객체의 상단이 기준선에 놓임을 의미하고, Bottom 수직 정렬은 객체의 하단이 기준선에 놓임을 의미합니다. 기본값: Position=Top인 경우 Bottom, Position=Bottom인 경우 Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```
**반환값:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```

그룹 문자에 대한 수직 정렬. 객체와 기준선 사이의 정렬을 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때, Top 수직 정렬은 객체의 상단이 기준선에 놓임을 의미하고, Bottom 수직 정렬은 객체의 하단이 기준선에 놓임을 의미합니다. 기본값: Position=Top인 경우 Bottom, Position=Bottom인 경우 Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```
**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

자식 요소 가져오기

**반환값:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

제어 문자 속성

**반환값:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps