---
title: IMathGroupingCharacter
second_title: Aspose.Slides لمرجع API لجافا
description: يحدد رمز تجميع فوق أو أسفل تعبير عادة لتسليط الضوء على العلاقة بين العناصر
type: docs
url: /ar/com.aspose.slides/imathgroupingcharacter/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

يحدد رمز تجميع فوق أو أسفل تعبير، عادةً لتسليط الضوء على العلاقة بين العناصر

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## الأساليب

| الأسلوب | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل أساسي |
| [getCharacter()](#getCharacter--) | حرف التجميع القيمة الافتراضية: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | حرف التجميع القيمة الافتراضية: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | موضع حرف التجميع. |
| [setPosition(int value)](#setPosition-int-) | موضع حرف التجميع. |
| [getVerticalJustification()](#getVerticalJustification--) | المحاذاة العمودية لحرف التجميع. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | المحاذاة العمودية لحرف التجميع. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


معامل أساسي

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**قيمة الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


حرف التجميع القيمة الافتراضية: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // قوس سفلي
> ```

**قيمة الإرجاع:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


حرف التجميع القيمة الافتراضية: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // قوس سفلي
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


موضع حرف التجميع. القيمة الافتراضية: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**قيمة الإرجاع:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


موضع حرف التجميع. القيمة الافتراضية: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```


المحاذاة العمودية لحرف التجميع. تحدد موضع الكائن بالنسبة إلى خط الأساس. على سبيل المثال، عندما يكون حرف التجميع فوق الكائن، فإن VerticalJustification بقيمة Top تعني أن أعلى الكائن يقع على خط الأساس؛ وعندما تكون VerticalJustification مضبوطة على Bottom، يكون أسفل الكائن على خط الأساس. القيمة الافتراضية: Bottom عندما تكون Position=Top، وTop عندما تكون Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**قيمة الإرجاع:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```


المحاذاة العمودية لحرف التجميع. تحدد موضع الكائن بالنسبة إلى خط الأساس. على سبيل المثال، عندما يكون حرف التجميع فوق الكائن، فإن VerticalJustification بقيمة Top تعني أن أعلى الكائن يقع على خط الأساس؛ وعندما تكون VerticalJustification مضبوطة على Bottom، يكون أسفل الكائن على خط الأساس. القيمة الافتراضية: Bottom عندما تكون Position=Top، وTop عندما تكون Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |