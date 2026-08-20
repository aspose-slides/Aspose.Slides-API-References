---
title: MathGroupingCharacter
second_title: Aspose.Slides 的 Java API 參考
description: 指定在表達式之上或之下的分組符號，通常用於突顯元素之間的關係
type: docs
url: /zh-hant/com.aspose.slides/mathgroupingcharacter/
---
**繼承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有已實作的介面：**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

指定在表達式之上或之下的分組符號，通常用於突顯元素之間的關係

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | 初始化 MathGroupingCharacter 類別的新執行個體，使用預設的分組字元 U+23DF（底部大括弧） |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | 初始化 MathGroupingCharacter 類別的新執行個體。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getCharacter()](#getCharacter--) | 分組字元 預設值：U+23DF（底部大括弧） |
| [setCharacter(char value)](#setCharacter-char-) | 分組字元 預設值：U+23DF（底部大括弧） |
| [getPosition()](#getPosition--) | 分組字元的位置。 |
| [setPosition(int value)](#setPosition-int-) | 分組字元的位置。 |
| [getVerticalJustification()](#getVerticalJustification--) | 群組字元的垂直對齊方式。 |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | 群組字元的垂直對齊方式。 |
| [getChildren()](#getChildren--) | 取得子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


初始化 MathGroupingCharacter 類別的新執行個體，使用預設的分組字元 U+23DF（底部大括弧）

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用 bar 的基礎元素 |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


初始化 MathGroupingCharacter 類別的新執行個體。

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用 bar 的基礎元素 |
| character | char | 分組字元 |
| position | int | 分組字元的位置 |
| verticalJustification | int | 群組字元的垂直對齊方式 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


基礎參數

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**傳回：**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


分組字元 預設值：U+23DF（底部大括弧）

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 底部圓括號
> ```

**傳回：**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```


分組字元 預設值：U+23DF（底部大括弧）

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 底部圓括號
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


分組字元的位置。預設：底部

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**傳回：**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


分組字元的位置。預設：底部

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```


群組字元的垂直對齊方式。指定物件相對於基線的對齊方式。例如，當群組字元位於物件上方時，VerticalJustification 為 Top 表示物件的頂部落在基線上；當 VerticalJustification 設為 Bottom 時，物件的底部落在基線上。預設值：當 Position=Top 時為 Bottom，當 Position=Bottom 時為 Top。

--------------------

> ```
public final int getVerticalJustification()
```

**傳回：**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```


群組字元的垂直對齊方式。指定物件相對於基線的對齊方式。例如，當群組字元位於物件上方時，VerticalJustification 為 Top 表示物件的頂部落在基線上；當 VerticalJustification 設為 Bottom 時，物件的底部落在基線上。預設值：當 Position=Top 時為 Bottom，當 Position=Bottom 時為 Top。

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


取得子元素

**傳回：**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Control Character Properties

**傳回：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps