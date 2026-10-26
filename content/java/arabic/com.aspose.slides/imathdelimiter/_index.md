---
title: IMathDelimiter
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يحدد كائن الفاصل الذي يتكون من أحرف الفتح والإغلاق مثل الأقواس، الأقواس المعقوفة، الأقواس المربعة والشرطات العمودية، ويحتوي على عنصر أو أكثر رياضيًا داخله مفصولًا بحرف محدد.
type: docs
url: /ar/com.aspose.slides/imathdelimiter/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

يحدد كائن الفاصل، المكوّن من أحرف البداية والنهاية (مثل الأقواس، الأقواس المعقوفة، الأقواس المربعة، والشرطات العمودية)، وواحد أو أكثر من العناصر الرياضية داخله، مفصولًا بواسطة حرف محدد. أمثلة: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getArguments()](#getArguments--) | عنصر أو أكثر رياضي مفصول بأحرف الفاصل |
| [getBeginningCharacter()](#getBeginningCharacter--) | حرف بداية الفاصل يحدد حرف الفاصل البداية أو الفتح |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | حرف بداية الفاصل يحدد حرف الفاصل البداية أو الفتح |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | حرف فاصلة الفاصل يحدد الحرف الذي يفصل المعاملات في كائن الفاصل |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | حرف فاصلة الفاصل يحدد الحرف الذي يفصل المعاملات في كائن الفاصل |
| [getEndingCharacter()](#getEndingCharacter--) | حرف نهاية الفاصل يحدد حرف الفاصل النهاية أو الإغلاق |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | حرف نهاية الفاصل يحدد حرف الفاصل النهاية أو الإغلاق |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | يحدد نمو BeginningCharacter, SeparatorCharacter, EndingCharacter. عندما تكون true، ينمو الفاصل عموديًا لمطابقة ارتفاع المعامل |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | يحدد نمو BeginningCharacter, SeparatorCharacter, EndingCharacter. عندما تكون true، ينمو الفاصل عموديًا لمطابقة ارتفاع المعامل |
| [getDelimiterShape()](#getDelimiterShape--) | يحدد شكل الفواصل في كائن الفاصل |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | يحدد شكل الفواصل في كائن الفاصل |
| [delimit(char separatorCharacter)](#delimit-char-) | يفصل المعاملات باستخدام حرف الفاصل المحدد |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

عنصر أو أكثر رياضي مفصول بأحرف الفاصل

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
public abstract char getBeginningCharacter()
```

حرف بداية الفاصل يحدد حرف الفاصل البداية أو الفتح. الفواصل الرياضية هي أحرف محيطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: '('.

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
public abstract void setBeginningCharacter(char value)
```

حرف بداية الفاصل يحدد حرف الفاصل البداية أو الفتح. الفواصل الرياضية هي أحرف محيطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

حرف فاصلة الفاصل يحدد الحرف الذي يفصل المعاملات في كائن الفاصل. الافتراضي: '|'.

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
public abstract void setSeparatorCharacter(char value)
```

حرف فاصلة الفاصل يحدد الحرف الذي يفصل المعاملات في كائن الفاصل. الافتراضي: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

حرف نهاية الفاصل يحدد حرف الفاصل النهاية أو الإغلاق. الفواصل الرياضية هي أحرف محيطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'.

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
public abstract void setEndingCharacter(char value)
```

حرف نهاية الفاصل يحدد حرف الفاصل النهاية أو الإغلاق. الفواصل الرياضية هي أحرف محيطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

يحدد نمو BeginningCharacter, SeparatorCharacter, EndingCharacter. عندما تكون true، ينمو الفاصل عموديًا لمطابقة ارتفاع المعامل. القيمة الافتراضية هي true

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
public abstract void setGrowToMatchOperandHeight(boolean value)
```

يحدد نمو BeginningCharacter, SeparatorCharacter, EndingCharacter. عندما تكون true، ينمو الفاصل عموديًا لمطابقة ارتفاع المعامل. القيمة الافتراضية هي true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

يحدد شكل الفواصل في كائن الفاصل. عندما يكون MathDelimiterShape.Centered، تكون الفواصل مركَّزة حول محور الرياضيات للنص الرياضي ولا تزال تتناسب مع الارتفاع الكامل لمحتواها. عندما يكون MathDelimiterShape.Match، يتم تعديل ارتفاعها وشكلها لتطابق محتواها تمامًا.

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
public abstract void setDelimiterShape(int value)
```

يحدد شكل الفواصل في كائن الفاصل. عندما يكون MathDelimiterShape.Centered، تكون الفواصل مركَّزة حول محور الرياضيات للنص الرياضي ولا تزال تتناسب مع الارتفاع الكامل لمحتواها. عندما يكون MathDelimiterShape.Match، يتم تعديل ارتفاعها وشكلها لتطابق محتواها تمامًا.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

يفصل المعاملات باستخدام حرف الفاصل المحدد

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| separatorCharacter | char | حرف الفاصل |

**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - هذا الكائن بعد تطبيق حرف الفاصل