---
title: MathDelimiter
second_title: مرجع API ل Aspose.Slides للـ Java
description: يحدّد كائن الفاصل الذي يتكوّن من أحرف الفتح والإغلاق مثل الأقواس، الأقواس المعقوفة، الأقواس المربعة، والشرطة العمودية، ويحتوي على عنصر أو أكثر من العناصر الرياضية داخله مفصولةً بحرف محدد.
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

يحدد كائن الفاصل، المكوّن من أحرف الفتح والإغلاق (مثل الأقواس، الأقواس المعقوفة، الأقواس المربعة، والشرطة العمودية)، وواحد أو أكثر من العناصر الرياضية داخله، مفصولةً بحرف محدد. أمثلة: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | يُهيئ MathDelimiter بالعنصر المحدد كمعامل أساسي مفرد |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getArguments()](#getArguments--) | واحد أو أكثر من العناصر الرياضية مفصولةً بأحرف الفاصل |
| [getBeginningCharacter()](#getBeginningCharacter--) | حرف البداية للفاصل يحدد الحرف البداية، أو الحرف الافتتاحي للفاصل. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | حرف البداية للفاصل يحدد الحرف البداية، أو الحرف الافتتاحي للفاصل. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | حرف الفاصل الفاصل يحدد الحرف الذي يفصل بين المعاملات في كائن الفاصل. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | حرف الفاصل الفاصل يحدد الحرف الذي يفصل بين المعاملات في كائن الفاصل. |
| [getEndingCharacter()](#getEndingCharacter--) | حرف النهاية للفاصل يحدد الحرف النهائي، أو الحرف الختامي للفاصل. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | حرف النهاية للفاصل يحدد الحرف النهائي، أو الحرف الختامي للفاصل. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما تكون true، ينمو الفاصل عموديًا ليتطابق مع ارتفاع المعامل. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما تكون true، ينمو الفاصل عموديًا ليتطابق مع ارتفاع المعامل. |
| [getDelimiterShape()](#getDelimiterShape--) | يحدد شكل الفواصل في كائن الفاصل. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | يحدد شكل الفواصل في كائن الفاصل. |
| [delimit(char separatorCharacter)](#delimit-char-) | يفصل بين المعاملات باستخدام حرف الفاصل المحدد |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | يحيط عنصر رياضي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [getChildren()](#getChildren--) | احصل على العناصر الفرعية |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

يُهيئ MathDelimiter بالعنصر المحدد كمعامل أساسي مفرد

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

واحد أو أكثر من العناصر الرياضية مفصولةً بأحرف الفاصل

--------------------

> ```
> مثال:
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

حرف البداية للفاصل يحدد الحرف البداية، أو الحرف الافتتاحي للفاصل. الفواصل الرياضية هي أحرف محيطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: '('.

--------------------

> ```
> مثال:
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

حرف البداية للفاصل يحدد الحرف البداية، أو الحرف الافتتاحي للفاصل. الفواصل الرياضية هي أحرف محيطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: '('.

--------------------

> ```
> مثال:
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

حرف الفاصل الفاصل يحدد الحرف الذي يفصل بين المعاملات في كائن الفاصل. القيمة الافتراضية: '|'.

--------------------

> ```
> مثال:
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

حرف الفاصل الفاصل يحدد الحرف الذي يفصل بين المعاملات في كائن الفاصل. القيمة الافتراضية: '|'.

--------------------

> ```
> مثال:
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

حرف النهاية للفاصل يحدد الحرف النهائي، أو الحرف الختامي للفاصل. الفواصل الرياضية هي أحرف محيطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'.

--------------------

> ```
> مثال:
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

حرف النهاية للفاصل يحدد الحرف النهائي، أو الحرف الختامي للفاصل. الفواصل الرياضية هي أحرف محيطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'.

--------------------

> ```
> مثال:
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

يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما تكون true، ينمو الفاصل عموديًا ليتطابق مع ارتفاع المعامل. القيمة الافتراضية هي true

--------------------

> ```
> مثال:
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

يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما تكون true، ينمو الفاصل عموديًا ليتطابق مع ارتفاع المعامل. القيمة الافتراضية هي true

--------------------

> ```
> مثال:
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

يحدد شكل الفواصل في كائن الفاصل. عندما يكون MathDelimiterShape.Centered، تكون الفواصل متمركزة حول محور الرياضيات للنص الرياضي وتظل مصممة لتناسب الارتفاع الكامل لمحتوياتها. عندما يكون MathDelimiterShape.Match، يتغير ارتفاعها وشكلها لتطابق محتوياتها تمامًا.

--------------------

> ```
> مثال:
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

يحدد شكل الفواصل في كائن الفاصل. عندما يكون MathDelimiterShape.Centered، تكون الفواصل متمركزة حول محور الرياضيات للنص الرياضي وتظل مصممة لتناسب الارتفاع الكامل لمحتوياتها. عندما يكون MathDelimiterShape.Match، يتغير ارتفاعها وشكلها لتطابق محتوياتها تمامًا.

--------------------

> ```
> مثال
```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

يفصل بين المعاملات باستخدام حرف الفاصل المحدد

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

يحيط عنصر رياضي بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار

--------------------

> ```
> مثال:
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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - إذا كان beginningCharacter و endingCharacter null، تُعيّن الخصائص المقابلة قيمًا فقط ولا يُنشئ كائنًا جديدًا (يرجع هذه الحالة). وإلا، يرجع عنصر رياضي جديد من النوع Delimiter يتضمن الأحرف المحددة كإطار وهذه الحالة من [MathDelimiter](../../com.aspose.slides/mathdelimiter) مؤطّرة بالداخل.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

احصل على العناصر الفرعية

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

خصائص حرف التحكم

**القيمة المرجعة:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps