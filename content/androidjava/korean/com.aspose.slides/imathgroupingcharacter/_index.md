---
title: IMathGroupingCharacter
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 보통 요소 간의 관계를 강조하기 위해 식 위 또는 아래에 그룹화 기호를 지정합니다.
type: docs
url: /ko/com.aspose.slides/imathgroupingcharacter/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Specifies a grouping symbol above or below an expression, usually to highlight the relationship between elements  
→  
보통 요소 간의 관계를 강조하기 위해 식 위나 아래에 그룹화 기호를 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getCharacter()](#getCharacter--) | Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Position of grouping character. |
| [setPosition(int value)](#setPosition-int-) | Position of grouping character. |
| [getVerticalJustification()](#getVerticalJustification--) | Vertical justification of group character. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Vertical justification of group character. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Base argument  
→  
기본 인수

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET)  
→  
그룹화 문자 기본값: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 아래 괄호
> ```

**Returns:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET)  
→  
그룹화 문자 기본값: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 아래 괄호
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Position of grouping character. Default: Bottom  
→  
그룹화 문자 위치. 기본값: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Position of grouping character. Default: Bottom  
→  
그룹화 문자 위치. 기본값: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline Default: Bottom for Position=Top, and Top for Position=Bottom  
→  
그룹 문자 수직 정렬. 객체가 기준선에 대해 어떻게 정렬되는지를 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 경우, VerticalJustification of Top은 객체의 상단이 기준선에 맞춰짐을 의미합니다; VerticalJustification이 Bottom으로 설정되면 객체의 하단이 기준선에 맞춰집니다. 기본값: Position=Top인 경우 Bottom, Position=Bottom인 경우 Top.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Returns:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline Default: Bottom for Position=Top, and Top for Position=Bottom  
→  
그룹 문자 수직 정렬. 객체가 기준선에 대해 어떻게 정렬되는지를 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 경우, VerticalJustification of Top은 객체의 상단이 기준선에 맞춰짐을 의미합니다; VerticalJustification이 Bottom으로 설정되면 객체의 하단이 기준선에 맞춰집니다. 기본값: Position=Top인 경우 Bottom, Position=Bottom인 경우 Top.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |