---
title: MathGroupingCharacter
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يحدد رمز تجميع فوق أو أسفل تعبير عادة لتسليط الضوء على العلاقة بين العناصر
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

يحدد رمز تجميع فوق أو أسفل تعبير، عادةً لتسليط الضوء على العلاقة بين العناصر

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | يُهيّئ مثيلًا جديدًا من فئة MathGroupingCharacter باستخدام الحرف التجميعي الافتراضي U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | يُهيّئ مثيلًا جديدًا من فئة MathGroupingCharacter. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | المُعامل الأساسي |
| [getCharacter()](#getCharacter--) | قيمة الحرف التجميعي الافتراضية: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | قيمة الحرف التجميعي الافتراضية: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | موضع الحرف التجميعي. |
| [setPosition(int value)](#setPosition-int-) | موضع الحرف التجميعي. |
| [getVerticalJustification()](#getVerticalJustification--) | المبرر العمودي للحرف التجميعي. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | المبرر العمودي للحرف التجميعي. |
| [getChildren()](#getChildren--) | جلب عناصر الأطفال |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


يُهيّئ مثيلًا جديدًا من فئة MathGroupingCharacter باستخدام الحرف التجميعي الافتراضي U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبق عليه الشريط |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


يُهيّئ مثيلًا جديدًا من فئة MathGroupingCharacter.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبق عليه الشريط |
| character | char | حرف التجميع |
| position | int | موضع الحرف التجميعي |
| verticalJustification | int | المبرر العمودي للحرف التجميعي |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


المُعامل الأساسي

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**القيمة المرتجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


قيمة الحرف التجميعي الافتراضية: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // قوس سفلي
> ```

**القيمة المرتجعة:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```


قيمة الحرف التجميعي الافتراضية: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // قوس سفلي
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


موضع الحرف التجميعي. الافتراضي: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**القيمة المرتجعة:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


موضع الحرف التجميعي. الافتراضي: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```


المبرر العمودي للحرف التجميعي. يحدد محاذاة الكائن بالنسبة إلى الخط الأساسي. على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، يشير المبرر العمودي Top إلى أن أعلى الكائن يقع على الخط الأساسي؛ عندما يُضبط المبرر العمودي على Bottom، يكون أسفل الكائن على الخط الأساسي. الافتراضي: Bottom لـ Position=Top، و Top لـ Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**القيمة المرتجعة:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```


المبرر العمودي للحرف التجميعي. يحدد محاذاة الكائن بالنسبة إلى الخط الأساسي. على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، يشير المبرر العمودي Top إلى أن أعلى الكائن يقع على الخط الأساسي؛ عندما يُضبط المبرر العمودي على Bottom، يكون أسفل الكائن على الخط الأساسي. الافتراضي: Bottom لـ Position=Top، و Top لـ Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


جلب عناصر الأطفال

**القيمة المرتجعة:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


خصائص حرف التحكم

**القيمة المرتجعة:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps