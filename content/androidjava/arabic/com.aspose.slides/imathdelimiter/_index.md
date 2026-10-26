---
title: IMathDelimiter
second_title: Aspose.Slides لنظام Android عبر مرجع API لل Java
description: يحدد كائن الفاصل المكوّن من أحرف الفتح والإغلاق مثل الأقواس، الأقواس المعقوفة، الأقواس المربعة والشرطات العمودية، بالإضافة إلى عنصر أو أكثر رياضي داخلها، مفصولين بحرف محدد.
type: docs
url: /ar/com.aspose.slides/imathdelimiter/
---
**جميع الواجهات المطبقة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

يحدد كائن الفاصل، المكوَّن من أحرف الفتح والإغلاق (مثل الأقواس، الأقواس المعقوفة، الأقواس المربعة، والشرطات العمودية)، وعنصر أو أكثر رياضي داخلها، مفصولة بحرف محدد. أمثلة: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [getBeginningCharacter()](#getBeginningCharacter--) | حرف بداية الفاصل يحدد حرف الفاصل الأول، أو حرف الفتح. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | حرف بداية الفاصل يحدد حرف الفاصل الأول، أو حرف الفتح. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | حرف فاصل الفواصل يحدد الحرف الذي يفصل الوسائط في كائن الفاصل. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | حرف فاصل الفواصل يحدد الحرف الذي يفصل الوسائط في كائن الفاصل. |
| [getEndingCharacter()](#getEndingCharacter--) | حرف نهاية الفاصل يحدد حرف الفاصل الأخير، أو حرف الإغلاق. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | حرف نهاية الفاصل يحدد حرف الفاصل الأخير، أو حرف الإغلاق. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما يكون true، ينمو الفواصل عموديًا لتطابق ارتفاع المعامل. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما يكون true، ينمو الفواصل عموديًا لتطابق ارتفاع المعامل. |
| [getDelimiterShape()](#getDelimiterShape--) | يحدد شكل الفواصل في كائن الفاصل. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | يحدد شكل الفواصل في كائن الفاصل. |
| [delimit(char separatorCharacter)](#delimit-char-) | يفصل الوسائط باستخدام حرف الفاصل المحدد |
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

حرف بداية الفاصل يحدد حرف الفاصل الأول، أو حرف الفتح. الفواصل الرياضية هي أحرف إحاطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: '('.

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

حرف بداية الفاصل يحدد حرف الفاصل الأول، أو حرف الفتح. الفواصل الرياضية هي أحرف إحاطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**معلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

حرف فاصل الفواصل يحدد الحرف الذي يفصل الوسائط في كائن الفاصل. القيمة الافتراضية: '|'.

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

حرف فاصل الفواصل يحدد الحرف الذي يفصل الوسائط في كائن الفاصل. القيمة الافتراضية: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**معلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

حرف نهاية الفاصل يحدد حرف الفاصل الأخير، أو حرف الإغلاق. الفواصل الرياضية هي أحرف إحاطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'.

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

حرف نهاية الفاصل يحدد حرف الفاصل الأخير، أو حرف الإغلاق. الفواصل الرياضية هي أحرف إحاطة مثل الأقواس، الأقواس المربعة، والأقواس المعقوفة. القيمة الافتراضية: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**معلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما يكون true، ينمو الفواصل عموديًا لتطابق ارتفاع المعامل. القيمة الافتراضية هي true

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

يحدد نمو BeginningCharacter و SeparatorCharacter و EndingCharacter. عندما يكون true، ينمو الفواصل عموديًا لتطابق ارتفاع المعامل. القيمة الافتراضية هي true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**معلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

يحدد شكل الفواصل في كائن الفاصل. عندما تكون MathDelimiterShape.Centered، تُوسَّط الفواصل حول محور الرياضيات للنص الرياضي وتُصمم لتناسب كامل ارتفاع محتواها. عندما تكون MathDelimiterShape.Match، يتم تعديل ارتفاعها وشكلها لتطابق محتواها بالضبط.

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

يحدد شكل الفواصل في كائن الفاصل. عندما تكون MathDelimiterShape.Centered، تُوسَّط الفواصل حول محور الرياضيات للنص الرياضي وتُصمم لتناسب كامل ارتفاع محتواها. عندما تكون MathDelimiterShape.Match، يتم تعديل ارتفاعها وشكلها لتطابق محتواها بالضبط.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**معلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

يفصل الوسائط باستخدام حرف الفاصل المحدد

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**معلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| separatorCharacter | char | حرف الفاصل |

**القيمة المرجعة:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - هذا الكائن بعد تطبيق حرف الفاصل