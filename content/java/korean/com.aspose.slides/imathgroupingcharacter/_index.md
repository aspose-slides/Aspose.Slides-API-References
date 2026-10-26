---
title: IMathGroupingCharacter
second_title: Aspose.Slides for Java API 레퍼런스
description: 보통 요소 간의 관계를 강조하기 위해 표현식 위나 아래에 그룹화 기호를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathgroupingcharacter/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

표현식 위 또는 아래에 그룹화 기호를 지정하며, 일반적으로 요소 간의 관계를 강조하기 위해 사용됩니다

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
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
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
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
public abstract char getCharacter()
```


그룹화 문자 기본값: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 아래 괄호
> ```

**반환값:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


그룹화 문자 기본값: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 아래 괄호
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


그룹화 문자의 위치. 기본값: Bottom

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
public abstract void setPosition(int value)
```


그룹화 문자의 위치. 기본값: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```


그룹 문자에 대한 수직 정렬. 객체가 기준선에 대해 어떻게 정렬되는지를 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때, 수직 정렬이 Top이면 객체의 상단이 기준선에 맞춰지고, Bottom으로 설정하면 객체의 하단이 기준선에 맞춰집니다. 기본값: Position=Top 일 때 Bottom, Position=Bottom 일 때 Top

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
public abstract void setVerticalJustification(int value)
```


그룹 문자에 대한 수직 정렬. 객체가 기준선에 대해 어떻게 정렬되는지를 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때, 수직 정렬이 Top이면 객체의 상단이 기준선에 맞춰지고, Bottom으로 설정하면 객체의 하단이 기준선에 맞춰집니다. 기본값: Position=Top 일 때 Bottom, Position=Bottom 일 때 Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |