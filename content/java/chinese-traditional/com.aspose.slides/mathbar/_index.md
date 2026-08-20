---
title: MathBar
second_title: Aspose.Slides for Java API 參考
description: 指定 bar 函式，由基礎參數和上橫線或下橫線組成
type: docs
url: /zh-hant/com.aspose.slides/mathbar/
---
**繼承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有已實作的介面:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

指定 bar 函式，由基礎參數和上橫線或下橫線組成

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | 使用上橫線 (頂部位置) 初始化 MathBar |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | 使用指定位置初始化 MathBar |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getPosition()](#getPosition--) | 條線的位置。 |
| [setPosition(int value)](#setPosition-int-) | 條線的位置。 |
| [getChildren()](#getChildren--) | 取得子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字元屬性 |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```


使用上橫線 (頂部位置) 初始化 MathBar

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用 bar 的基礎元素 |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```


使用指定位置初始化 MathBar

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用 bar 的基礎元素 |
| position | int | 條線的位置。 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


基礎參數

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**回傳值:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


條線的位置。預設：頂部

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```


**回傳值:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


條線的位置。預設：頂部

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


取得子元素

**回傳值:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


控制字元屬性

**回傳值:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps