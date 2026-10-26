---
title: MathBar
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 指定 bar 功能，由基底參數以及上劃線或下劃線組成
type: docs
url: /zh-hant/com.aspose.slides/mathbar/
---
**繼承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有實作的介面：**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

指定 bar 功能，由基底參數以及上劃線或下劃線組成

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | 使用上劃線 (Top 位置) 初始化 MathBar |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | 使用指定位置初始化 MathBar |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基底參數 |
| [getPosition()](#getPosition--) | Bar 線的位置。 |
| [setPosition(int value)](#setPosition-int-) | Bar 線的位置。 |
| [getChildren()](#getChildren--) | 取得子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字元屬性 |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```


使用上劃線 (Top 位置) 初始化 MathBar

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用 bar 的基底元素 |

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 套用 bar 的基底元素 |
| position | int | Bar 線的位置。 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


基底參數

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**傳回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Bar 線的位置。預設：Top

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**傳回值：**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Bar 線的位置。預設：Top

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
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

**傳回值：**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


控制字元屬性

**傳回值：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps