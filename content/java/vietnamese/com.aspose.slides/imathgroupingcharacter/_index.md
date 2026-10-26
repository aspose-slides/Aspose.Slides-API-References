---
title: IMathGroupingCharacter
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định ký hiệu nhóm ở trên hoặc dưới một biểu thức, thường để làm nổi bật mối quan hệ giữa các phần tử
type: docs
url: /vi/com.aspose.slides/imathgroupingcharacter/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Xác định một ký hiệu nhóm ở trên hoặc dưới một biểu thức, thường để làm nổi bật mối quan hệ giữa các phần tử

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getCharacter()](#getCharacter--) | Grouping Character Giá trị mặc định: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Grouping Character Giá trị mặc định: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Vị trí của grouping character. |
| [setPosition(int value)](#setPosition-int-) | Vị trí của grouping character. |
| [getVerticalJustification()](#getVerticalJustification--) | Căn dọc của group character. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Că n dọc của group character. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Đối số cơ sở

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


Grouping Character Giá trị mặc định: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Dấu ngoặc dưới
```

**Returns:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


Grouping Character Giá trị mặc định: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Dấu ngoặc dưới
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Vị trí của grouping character. Mặc định: Bottom

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


Vị trí của grouping character. Mặc định: Bottom

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


Căn dọc của group character. Xác định việc căn chỉnh của đối tượng so với baseline. Ví dụ, khi group character nằm trên đối tượng, VerticalJustification của Top chỉ ra rằng phần trên của đối tượng nằm trên baseline; khi VerticalJustification được đặt thành Bottom, phần dưới của đối tượng nằm trên baseline. Mặc định: Bottom cho Position=Top, và Top cho Position=Bottom

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


Căn dọc của group character. Xác định việc căn chỉnh của đối tượng so với baseline. Ví dụ, khi group character nằm trên đối tượng, VerticalJustification của Top chỉ ra rằng phần trên của đối tượng nằm trên baseline; khi VerticalJustification được đặt thành Bottom, phần dưới của đối tượng nằm trên baseline. Mặc định: Bottom cho Position=Top, và Top cho Position=Bottom

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