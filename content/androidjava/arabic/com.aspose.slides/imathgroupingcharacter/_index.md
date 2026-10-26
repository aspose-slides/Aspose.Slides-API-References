---
title: IMathGroupingCharacter
second_title: مرجع API لجافا لـ Aspose.Slides لنظام Android
description: يحدد رمز تجميع فوق أو تحت تعبير عادةً لتسليط الضوء على العلاقة بين العناصر
type: docs
url: /ar/com.aspose.slides/imathgroupingcharacter/
---
**كل الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

يحدد رمز تجميع فوق أو تحت تعبير، عادةً لتسليط الضوء على العلاقة بين العناصر

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل القاعدة |
| [getCharacter()](#getCharacter--) | حرف التجميع القيمة الافتراضية: U+23DF (القوس المعقوف السفلي) |
| [setCharacter(char value)](#setCharacter-char-) | حرف التجميع القيمة الافتراضية: U+23DF (القوس المعقوف السفلي) |
| [getPosition()](#getPosition--) | موضع حرف التجميع. |
| [setPosition(int value)](#setPosition-int-) | موضع حرف التجميع. |
| [getVerticalJustification()](#getVerticalJustification--) | محاذاة رأسية لحرف المجموعة. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | محاذاة رأسية لحرف المجموعة. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


معامل القاعدة

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```


**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


حرف التجميع القيمة الافتراضية: U+23DF (القوس المعقوف السفلي)

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
public abstract void setCharacter(char value)
```


حرف التجميع القيمة الافتراضية: U+23DF (القوس المعقوف السفلي)

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
public abstract int getPosition()
```


موضع حرف التجميع. الافتراضي: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**الإرجاع:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


موضع حرف التجميع. الافتراضي: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```


محاذاة رأسية لحرف المجموعة. يحدد محاذاة الكائن بالنسبة إلى خط القاعدة. على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، تشير VerticalJustification إلى Top إلى أن أعلى الكائن يقع على خط القاعدة؛ عندما يتم تعيين VerticalJustification إلى Bottom، يكون أسفل الكائن على خط القاعدة. الافتراضي: Bottom عندما Position=Top، وTop عندما Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**الإرجاع:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```


محاذاة رأسية لحرف المجموعة. يحدد محاذاة الكائن بالنسبة إلى خط القاعدة. على سبيل المثال، عندما يكون حرف المجموعة فوق الكائن، تشير VerticalJustification إلى Top إلى أن أعلى الكائن يقع على خط القاعدة؛ عندما يتم تعيين VerticalJustification إلى Bottom، يكون أسفل الكائن على خط القاعدة. الافتراضي: Bottom عندما Position=Top، وTop عندما Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |