---
title: MathBar
second_title: Aspose.Slides for Java API Referansı
description: Temel argüman ve bir üst bar ya da alt bar içeren bar işlevini tanımlar
type: docs
url: /tr/com.aspose.slides/mathbar/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

Bar işlevini tanımlar, bir temel argüman ve üst bar ya da alt bar içerir

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Constructors

| Yapıcı | Açıklama |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | MathBar'ı üst bar (Üst konum) ile başlatır |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | MathBar'ı belirtilen konumla başlatır |
## Methods

| Metod | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Temel argüman |
| [getPosition()](#getPosition--) | Bar çizgisinin konumu. |
| [setPosition(int value)](#setPosition-int-) | Bar çizgisinin konumu. |
| [getChildren()](#getChildren--) | Alt öğeleri al |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakteri Özellikleri |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```


MathBar'ı üst bar (Üst konum) ile başlatır

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**Parameters:**
| Parameter | Type | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Barın uygulandığı temel öğe |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```


MathBar'ı belirtilen konumla başlatır

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**Parameters:**
| Parameter | Type | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Barın uygulandığı temel öğe |
| position | int | Bar çizgisinin konumu. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Temel argüman

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Bar çizgisinin konumu. Varsayılan: Üst

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Bar çizgisinin konumu. Varsayılan: Üst

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Parameters:**
| Parameter | Type | Açıklama |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Alt öğeleri al

**Returns:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Kontrol Karakteri Özellikleri

**Returns:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps