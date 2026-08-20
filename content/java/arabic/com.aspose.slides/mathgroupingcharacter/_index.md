---
title: MathGroupingCharacter
second_title: Aspose.Slides لواجهة برمجة تطبيقات Java
description: يحدد رمز تجميع أعلى أو أسفل تعبير عادة لتسليط الضوء على العلاقة بين العناصر
type: docs
url: /ar/com.aspose.slides/mathgroupingcharacter/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

يحدد رمز تجميع أعلى أو أسفل تعبير، عادةً لتسليط الضوء على العلاقة بين العناصر

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | يَُهيئ نسخة جديدة من الفئة MathGroupingCharacter مع محرف التجميع الافتراضي U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | يَُهيئ نسخة جديدة من الفئة MathGroupingCharacter. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل أساسي |
| [getCharacter()](#getCharacter--) | محرف التجميع القيمة الافتراضية: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | محرف التجميع القيمة الافتراضية: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | موضع محرف التجميع. |
| [setPosition(int value)](#setPosition-int-) | موضع محرف التجميع. |
| [getVerticalJustification()](#getVerticalJustification--) | محاذاة عمودية لمحرف التجميع. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | محاذاة عمودية لمحرف التجميع. |
| [getChildren()](#getChildren--) | الحصول على العناصر الفرعية |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

يُهيئ نسخة جديدة من الفئة MathGroupingCharacter مع محرف التجميع الافتراضي U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبق عليه الشريط |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

يُهيئ نسخة جديدة من الفئة MathGroupingCharacter.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبق عليه الشريط |
| character | char | محرف التجميع |
| position | int | موضع محرف التجميع |
| verticalJustification | int | محاذاة عمودية لمحرف التجميع |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

معامل أساسي

--------------------

> ```
> مثال:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

قيمة محرف التجميع الافتراضية: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // القوس السفلي
> ```

**الإرجاع:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

قيمة محرف التجميع الافتراضية: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // القوس السفلي
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

موضع محرف التجميع. الافتراضي: Bottom

--------------------

> ```
> مثال:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setPosition(MathTopBotPositions.Top);
> ```

**الإرجاع:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

موضع محرف التجميع. الافتراضي: Bottom

--------------------

> ```
> مثال:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setPosition(MathTopBotPositions.Top);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```

محاذاة عمودية لمحرف التجميع. يحدد محاذاة الكائن بالنسبة إلى الخط الأساسي. على سبيل المثال، عندما يكون محرف التجميع أعلى الكائن، فإن VerticalJustification بقيمة Top يعني أن أعلى الكائن يقع على الخط الأساسي؛ عندما يُضبط VerticalJustification إلى Bottom، يكون أسفل الكائن على الخط الأساسي. الافتراضي: Bottom عندما Position=Top، وTop عندما Position=Bottom

--------------------

> ```
> مثال:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**الإرجاع:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```

محاذاة عمودية لمحرف التجميع. يحدد محاذاة الكائن بالنسبة إلى الخط الأساسي. على سبيل المثال، عندما يكون محرف التجميع أعلى الكائن، فإن VerticalJustification بقيمة Top يعني أن أعلى الكائن يقع على الخط الأساسي؛ عندما يُضبط VerticalJustification إلى Bottom، يكون أسفل الكائن على الخط الأساسي. الافتراضي: Bottom عندما Position=Top، وTop عندما Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setVerticalJustification(MathTopBotPositions.Top);
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