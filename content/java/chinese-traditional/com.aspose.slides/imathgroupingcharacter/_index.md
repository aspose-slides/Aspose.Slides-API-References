---
title: IMathGroupingCharacter
second_title: Aspose.Slides for Java API 參考
description: 指定表達式上方或下方的分組符號，通常用於突顯元素之間的關係
type: docs
url: /zh-hant/com.aspose.slides/imathgroupingcharacter/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

指定置於表達式上方或下方的群組符號，通常用以凸顯元素之間的關係

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getCharacter()](#getCharacter--) | Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | 群組字元的位置。 |
| [setPosition(int value)](#setPosition-int-) | 群組字元的位置。 |
| [getVerticalJustification()](#getVerticalJustification--) | 群組字元的垂直對齊。 |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | 群組字元的垂直對齊。 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


基礎參數

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

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 底部括號
> ```

**Returns:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 底部括號
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


群組字元的位置。預設值：Bottom

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


群組字元的位置。預設值：Bottom

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


群組字元的垂直對齊。指定物件相對於基線的對齊方式。例如，當群組字元位於物件上方時，VerticalJustification 為 Top 表示物件的頂部落在基線上；當 VerticalJustification 設為 Bottom 時，物件的底部落在基線上。預設值：當 Position 為 Top 時為 Bottom，當 Position 為 Bottom 時為 Top

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


群組字元的垂直對齊。指定物件相對於基線的對齊方式。例如，當群組字元位於物件上方時，VerticalJustification 為 Top 表示物件的頂部落在基線上；當 VerticalJustification 設為 Bottom 時，物件的底部落在基線上。預設值：當 Position 為 Top 時為 Bottom，當 Position 為 Bottom 時為 Top

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