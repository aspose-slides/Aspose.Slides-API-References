---
title: MathBar
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يحدد وظيفة الشريط التي تتكون من معامل أساسي وشريط فوقي أو سفلي
type: docs
url: /ar/com.aspose.slides/mathbar/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

يحدد وظيفة الشريط، المكوّن من معامل أساسي وشريط فوقي أو سفلي

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | يقوم بتهيئة MathBar مع شريط فوق (الموضع أعلى) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | يقوم بتهيئة MathBar مع الموضع المحدد |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل أساسي |
| [getPosition()](#getPosition--) | موضع خط الشريط. |
| [setPosition(int value)](#setPosition-int-) | موضع خط الشريط. |
| [getChildren()](#getChildren--) | الحصول على العناصر الفرعية |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```

يقوم بتهيئة MathBar مع شريط فوق (الموضع أعلى)

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبق عليه الشريط |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```

يقوم بتهيئة MathBar مع الموضع المحدد

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبق عليه الشريط |
| position | int | موضع خط الشريط. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

المعامل الأساسي

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```


**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

موضع خط الشريط. الافتراضي: أعلى

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**الإرجاع:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

موضع خط الشريط. الافتراضي: أعلى

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

الحصول على العناصر الفرعية

**الإرجاع:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

خصائص حرف التحكم

**الإرجاع:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps