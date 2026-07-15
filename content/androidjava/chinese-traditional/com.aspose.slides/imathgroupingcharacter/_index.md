---
title: IMathGroupingCharacter
second_title: Aspose.Slides for Android via Java API 參考
description: 指定一個位於表達式上方或下方的分組符號，通常用於突顯元素之間的關係
type: docs
url: /zh-hant/com.aspose.slides/imathgroupingcharacter/
---
**已實作的介面:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

指定一個位於表達式上方或下方的分組符號，通常用於突顯元素之間的關係

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
```
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getCharacter()](#getCharacter--) | 分組字元 預設值: U+23DF (底部大括號) |
| [setCharacter(char value)](#setCharacter-char-) | 分組字元 預設值: U+23DF (底部大括號) |
| [getPosition()](#getPosition--) | 分組字元的位置。 |
| [setPosition(int value)](#setPosition-int-) | 分組字元的位置。 |
| [getVerticalJustification()](#getVerticalJustification--) | 分組字元的垂直對齊方式。 |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | 分組字元的垂直對齊方式。 |
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

**返回:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


分組字元 預設值: U+23DF (底部大括號)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 底部括號
> ```

**返回:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


分組字元 預設值: U+23DF (底部大括號)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 底部括號
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


分組字元的位置。預設值: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**返回:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


分組字元的位置。預設值: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```


分組字元的垂直對齊方式。指定物件相對於基線的對齊方式。例如，當分組字元位於物件上方時，VerticalJustification 為 Top 表示物件的頂部位於基線上；當 VerticalJustification 設為 Bottom 時，物件的底部位於基線上。預設值: Position=Top 時為 Bottom，Position=Bottom 時為 Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**返回:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```


分組字元的垂直對齊方式。指定物件相對於基線的對齊方式。例如，當分組字元位於物件上方時，VerticalJustification 為 Top 表示物件的頂部位於基線上；當 VerticalJustification 設為 Bottom 時，物件的底部位於基線上。預設值: Position=Top 時為 Bottom，Position=Bottom 時為 Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |