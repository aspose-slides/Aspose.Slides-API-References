---
title: MathDelimiter
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد كائن الفاصل المكوّن من أحرف الفتح والإغلاق مثل الأقواس والأقواس المعقوفة والأقواس المربعة والقضبان العمودية، وعنصر أو أكثر رياضي داخلها مفصولين بحرف محدد.
type: docs
url: /ar/com.aspose.slides/mathdelimiter/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

يحدد كائن الفاصل، المكوّن من أحرف الفتح والإغلاق (مثل الأقواس، الأقواس المعقوفة، الأقواس المربعة، والأشرطة العمودية)، وعنصر أو أكثر رياضي داخلها، مفصولة بحرف محدد. أمثلة: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | يُهيئ MathDelimiter بالعنصر المحدد كحجة أساسية واحدة |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getArguments()](#getArguments--) | عنصر أو أكثر رياضي مفصول بحرف الفاصل |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character يحدد حرف الفاصل الافتتاحي، أو حرف الفتح. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character يحدد حرف الفاصل الافتتاحي، أو حرف الفتح. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character يحدد الحرف الذي يفصل بين الحجج في كائن الفاصل. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character يحدد الحرف الذي يفصل بين الحجج في كائن الفاصل. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character يحدد حرف الفاصل الختامي، أو حرف الإغلاق. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character يحدد حرف الفاصل الختامي، أو حرف الإغلاق. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما يكون true، ينمو الفاصل عموديًا لمطابقة ارتفاع العامل. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما يكون true، ينمو الفاصل عموديًا لمطابقة ارتفاع العامل. |
| [getDelimiterShape()](#getDelimiterShape--) | يحدد شكل الفواصل في كائن الفاصل. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | يحدد شكل الفواصل في كائن الفاصل. |
| [delimit(char separatorCharacter)](#delimit-char-) | يفصل الحجج باستخدام حرف الفاصل المحدد |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | يغلف عنصر رياضي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [getChildren()](#getChildren--) | إحضار عناصر الأطفال |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |

### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

يُهيئ MathDelimiter بالعنصر المحدد كحجة أساسية واحدة

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبق عليه الفاصل. يمكن أن يكون null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

عنصر أو أكثر رياضي مفصول بحروف الفاصل

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**القيمة المرجعة:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Delimiter Beginning Character يحدد حرف الفاصل الافتتاحي أو حرف الفتح. الفواصل الرياضية هي أحرف مغلقة مثل الأقواس، القوسين المربعتين، والأقواس المعقوفة. القيمة الافتراضية: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**القيمة المرجعة:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Delimiter Beginning Character يحدد حرف الفاصل الافتتاحي أو حرف الفتح. الفواصل الرياضية هي أحرف مغلقة مثل الأقواس، القوسين المربعتين، والأقواس المعقوفة. القيمة الافتراضية: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

Delimiter Separator Character يحدد الحرف الذي يفصل بين الحجج في كائن الفاصل. القيمة الافتراضية: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**القيمة المرجعة:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Delimiter Separator Character يحدد الحرف الذي يفصل بين الحجج في كائن الفاصل. القيمة الافتراضية: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

Delimiter Ending Character يحدد حرف الفاصل الختامي أو حرف الإغلاق. الفواصل الرياضية هي أحرف مغلقة مثل الأقواس، القوسين المربعتين، والأقواس المعقوفة. القيمة الافتراضية: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**القيمة المرجعة:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Delimiter Ending Character يحدد حرف الفاصل الختامي أو حرف الإغلاق. الفواصل الرياضية هي أحرف مغلقة مثل الأقواس، القوسين المربعتين، والأقواس المعقوفة. القيمة الافتراضية: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما يكون true، ينمو الفاصل عموديًا لمطابقة ارتفاع العامل. القيمة الافتراضية هي true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**القيمة المرجعة:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما يكون true، ينمو الفاصل عموديًا لمطابقة ارتفاع العامل. القيمة الافتراضية هي true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

يحدد شكل الفواصل في كائن الفاصل. عندما يكون MathDelimiterShape.Centered، تكون الفواصل متمركزة حول محور النص الرياضي وتظل مُصممة لتناسب كامل ارتفاع محتوياتها. عندما يكون MathDelimiterShape.Match، يتم تعديل ارتفاعها وشكلها لتطابق محتوياتها بدقة.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**القيمة المرجعة:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

يحدد شكل الفواصل في كائن الفاصل. عندما يكون MathDelimiterShape.Centered، تكون الفواصل متمركزة حول محور النص الرياضي وتظل مُصممة لتناسب كامل ارتفاع محتوياتها. عندما يكون MathDelimiterShape.Match، يتم تعديل ارتفاعها وشكلها لتطابق محتوياتها بدقة.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

يفصل الحجج باستخدام حرف الفاصل المحدد

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| separatorCharacter | char | حرف الفاصل |

**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - هذا الكائن بعد تطبيق حرف الفاصل
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

يغلف عنصر رياضي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| beginningCharacter | char | حرف البداية (عادة القوس الأيسر) |
| endingCharacter | char | حرف النهاية (عادة القوس الأيمن) |

**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - إذا كان beginningCharacter و endingCharacter قيمهما null، تُعيَّن الخصائص المقابلة قيمًا فقط ولا يُنشأ كائن جديد (يرجع هذا المثيل). وإلا، يرجع عنصر رياضي جديد من النوع Delimiter يتضمن الأحرف المحددة كإطار وهذا المثيل من [MathDelimiter](../../com.aspose.slides/mathdelimiter) مُؤطر داخله.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

إحضار عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

خصائص حرف التحكم

**القيمة المرجعة:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps