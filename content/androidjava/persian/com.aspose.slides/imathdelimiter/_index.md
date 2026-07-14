---
title: IMathDelimiter
second_title: مرجع API جاوا برای Aspose.Slides برای اندروید
description: شیء جداکننده را مشخص می‌کند که شامل کاراکترهای باز و بسته مانند پرانتز، کروشه، براکت و خطوط عمودی است و یک یا چند عنصر ریاضی درون آن که با یک کاراکتر مشخص جدا می‌شوند.
type: docs
url: /fa/com.aspose.slides/imathdelimiter/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

شیء جداکننده را مشخص می‌کند که شامل کاراکترهای باز و بسته (مانند پرانتز، کروشه، براکت و خطوط عمودی) و یک یا چند عنصر ریاضی درون آن است که با یک کاراکتر مشخص جدا می‌شوند. مثال‌ها: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

## متدها

| متد | توضیح |
| --- | --- |
| [getArguments()](#getArguments--) | یک یا چند عنصر ریاضی که با کاراکترهای جداکننده جدا شده‌اند |
| [getBeginningCharacter()](#getBeginningCharacter--) | کاراکتر شروع جداکننده، کاراکتر شروع یا باز شدن جداکننده را مشخص می‌کند. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | کاراکتر شروع جداکننده، کاراکتر شروع یا باز شدن جداکننده را مشخص می‌کند. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | کاراکتر جداکننده‌ی تفکیک‌کننده، کاراکتری را که آرگومان‌ها را در شیء جداکننده جدا می‌کند، مشخص می‌کند. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | کاراکتر جداکننده‌ی تفکیک‌کننده، کاراکتری را که آرگومان‌ها را در شیء جداکننده جدا می‌کند، مشخص می‌کند. |
| [getEndingCharacter()](#getEndingCharacter--) | کاراکتر پایان جداکننده، کاراکتر پایان یا بسته شدن جداکننده را مشخص می‌کند. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | کاراکتر پایان جداکننده، کاراکتر پایان یا بسته شدن جداکننده را مشخص می‌کند. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | رشد BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی مقدار true باشد، جداکننده‌ها به طور عمودی رشد می‌کنند تا با ارتفاع عملوند مطابقت داشته باشند. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | رشد BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی مقدار true باشد، جداکننده‌ها به طور عمودی رشد می‌کنند تا با ارتفاع عملوند مطابقت داشته باشند. |
| [getDelimiterShape()](#getDelimiterShape--) | شکل جداکننده‌ها در شیء جداکننده را مشخص می‌کند. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | شکل جداکننده‌ها در شیء جداکننده را مشخص می‌کند. |
| [delimit(char separatorCharacter)](#delimit-char-) | آرگومان‌ها را با استفاده از کاراکتر جداکننده‌ی مشخص شده جدا می‌کند |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

یک یا چند عنصر ریاضی که با کاراکترهای جداکننده جدا شده‌اند

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```


**باز می‌گردد:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```

کاراکتر شروع جداکننده، کاراکتر شروع یا باز شدن جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای محاطی مانند پرانتز، براکت و کروشه هستند. مقدار پیش‌فرض: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```


**باز می‌گردد:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```

کاراکتر شروع جداکننده، کاراکتر شروع یا باز شدن جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای محاطی مانند پرانتز، براکت و کروشه هستند. مقدار پیش‌فرض: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

کاراکتر جداکننده‌ی تفکیک‌کننده، کاراکتری را که آرگومان‌ها را در شیء جداکننده جدا می‌کند، مشخص می‌کند. مقدار پیش‌فرض: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**باز می‌گردد:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```

کاراکتر جداکننده‌ی تفکیک‌کننده، کاراکتری را که آرگومان‌ها را در شیء جداکننده جدا می‌کند، مشخص می‌کند. مقدار پیش‌فرض: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

کاراکتر پایان جداکننده، کاراکتر پایان یا بسته شدن جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای محاطی مانند پرانتز، براکت و کروشه هستند. مقدار پیش‌فرض: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**باز می‌گردد:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```

کاراکتر پایان جداکننده، کاراکتر پایان یا بسته شدن جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای محاطی مانند پرانتز، براکت و کروشه هستند. مقدار پیش‌فرض: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

رشد BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی مقدار true باشد، جداکننده‌ها به طور عمودی رشد می‌کنند تا با ارتفاع عملوند مطابقت داشته باشند. مقدار پیش‌فرض true است

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**باز می‌گردد:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

رشد BeginningCharacter، SeparatorCharacter و EndingCharacter را مشخص می‌کند. وقتی مقدار true باشد، جداکننده‌ها به طور عمودی رشد می‌کنند تا با ارتفاع عملوند مطابقت داشته باشند. مقدار پیش‌فرض true است

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

شکل جداکننده‌ها در شیء جداکننده را مشخص می‌کند. وقتی مقادیر MathDelimiterShape.Centered باشد، جداکننده‌ها حول محور ریاضی متن ریاضی متمرکز می‌شوند و همچنان می‌توانند تمام ارتفاع محتوا را پوشش دهند. وقتی مقادیر MathDelimiterShape.Match باشد، ارتفاع و شکل آن‌ها دقیقاً با محتوا مطابقت می‌یابد.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**باز می‌گردد:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```

شکل جداکننده‌ها در شیء جداکننده را مشخص می‌کند. وقتی مقادیر MathDelimiterShape.Centered باشد، جداکننده‌ها حول محور ریاضی متن ریاضی متمرکز می‌شوند و همچنان می‌توانند تمام ارتفاع محتوا را پوشش دهند. وقتی مقادیر MathDelimiterShape.Match باشد، ارتفاع و شکل آن‌ها دقیقاً با محتوا مطابقت می‌یابد.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

آرگومان‌ها را با کاراکتر جداکننده‌ی مشخص شده جدا می‌کند

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separatorCharacter | char | کاراکتر جداکننده |

**باز می‌گردد:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - این شیء پس از اعمال کاراکتر جداکننده