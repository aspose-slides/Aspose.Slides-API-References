---
title: MathBar
second_title: مرجع API Aspose.Slides للغة Java
description: تحدد دالة الشريط المتكوّنة من معامل أساسي وشريط علوي أو سفلي
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

تحدد دالة الشريط، المكوّنة من معامل أساسي وشريط علوي أو سفلي

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | يهيئ MathBar بشريط علوي (الموضع الأعلى) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | يهيئ MathBar بالموضع المحدد |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل أساسي |
| [getPosition()](#getPosition--) | موضع خط الشريط. |
| [setPosition(int value)](#setPosition-int-) | موضع خط الشريط. |
| [getChildren()](#getChildren--) | الحصول على عناصر الأطفال |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص أحرف التحكم |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```

يهيئ MathBar بشريط علوي (الموضع الأعلى)

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبّق عليه الشريط |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```

يهيئ MathBar بالموضع المحدد

--------------------

> ```
> مثال:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبّق عليه الشريط |
| position | int | موضع خط الشريط. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

معامل أساسي

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

موضع خط الشريط. الافتراضي: الأعلى

--------------------

> ```
> مثال:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**القيمة المرجعة:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

موضع خط الشريط. الافتراضي: الأعلى

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```


**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

الحصول على عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

خصائص أحرف التحكم

**القيمة المرجعة:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps