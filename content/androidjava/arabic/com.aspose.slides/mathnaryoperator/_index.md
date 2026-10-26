---
title: MathNaryOperator
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد كائنًا رياضيًا متعددًا مثل الجمع والتكامل.
type: docs
url: /ar/com.aspose.slides/mathnaryoperator/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات التي تم تنفيذها:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

يحدد كائنًا رياضيًا متعددًا، مثل الجمع (Summation) والتكامل (Integral). يتكون من عامل، وقاعدة (أو معامل)، وحدود علوية وسفلى اختيارية. من أمثلة العوامل المتعددة: الجمع، الاتحاد، التقاطع، التكامل

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يهيئ نسخة جديدة من الفئة MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يهيئ نسخة جديدة من الفئة MathNaryOperator. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | يهيئ نسخة جديدة من الفئة MathNaryOperator. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل القاعدة |
| [getSubscript()](#getSubscript--) | يحدد معامل المؤشر السفلي الذي، على سبيل المثال، في حالة التكامل، يضع الحد السفلي |
| [getSuperscript()](#getSuperscript--) | يحدد معامل المؤشر العلوي الذي، على سبيل المثال، في حالة التكامل، يضع الحد العلوي |
| [getOperator()](#getOperator--) | حرف عامل متعدد. على سبيل المثال: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | حرف عامل متعدد. على سبيل المثال: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | موقع الحدود (المؤشر السفلي والمؤشر العلوي) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | موقع الحدود (المؤشر السفلي والمؤشر العلوي) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | حرف العامل ينمو عموديًا ليتطابق مع ارتفاع المعامل |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | حرف العامل ينمو عموديًا ليتطابق مع ارتفاع المعامل |
| [getHideSubscript()](#getHideSubscript--) | إخفاء المؤشر السفلي |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | إخفاء المؤشر السفلي |
| [getHideSuperscript()](#getHideSuperscript--) | إخفاء المؤشر العلوي |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | إخفاء المؤشر العلوي |
| [getChildren()](#getChildren--) | احصل على عناصر الأطفال |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

يهيئ نسخة جديدة من الفئة MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operatorSymbol | char | رمز عامل متعدد |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | معامل القاعدة |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد السفلي |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد العلوي |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

يهيئ نسخة جديدة من الفئة MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operatorSymbol | char | رمز عامل متعدد |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | معامل القاعدة |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | الحد السفلي |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

يهيئ نسخة جديدة من الفئة MathNaryOperator.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operatorSymbol | char | رمز عامل متعدد |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | معامل القاعدة |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

معامل القاعدة

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

يحدد معامل المؤشر السفلي الذي، على سبيل المثال، في حالة التكامل، يضع الحد السفلي

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

يحدد معامل المؤشر العلوي الذي، على سبيل المثال، في حالة التكامل، يضع الحد العلوي

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```

حرف عامل متعدد. على سبيل المثال: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**القيمة المرجعة:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```

حرف عامل متعدد. على سبيل المثال: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```

موقع الحدود (المؤشر السفلي والمؤشر العلوي)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**القيمة المرجعة:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```

موقع الحدود (المؤشر السفلي والمؤشر العلوي)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

حرف العامل ينمو عموديًا ليتطابق مع ارتفاع المعامل

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**القيمة المرجعة:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

حرف العامل ينمو عموديًا ليتطابق مع ارتفاع المعامل

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```

إخفاء المؤشر السفلي

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**القيمة المرجعة:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```

إخفاء المؤشر السفلي

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```

إخفاء المؤشر العلوي

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**القيمة المرجعة:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```

إخفاء المؤشر العلوي

--------------------

> ```
> Example:
>  
     ... (capture  ... ... ... ) 
```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

احصل على عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

خصائص حرف التحكم

**القيمة المرجعة:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps