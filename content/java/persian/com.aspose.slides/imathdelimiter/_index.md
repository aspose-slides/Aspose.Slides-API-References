---
title: IMathDelimiter
second_title: مرجع API Aspose.Slides برای جاوا
description: شیء جداکننده را که شامل کاراکترهای باز و بسته مانند پرانتز، کروشه، قلاب و نوارهای عمودی است و یک یا چند عنصر ریاضی داخل آن را که با یک کاراکتر مشخص جدا می‌شوند، مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/imathdelimiter/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

شیء جداکننده را مشخص می‌کند که شامل کاراکترهای باز و بسته (مانند پرانتز، کروشه، قلاب و نوارهای عمودی) و یک یا چند عنصر ریاضی داخل آن است که با یک کاراکتر مشخص جدا می‌شوند. مثال‌ها: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [getBeginningCharacter()](#getBeginningCharacter--) | کاراکتر شروع جداکننده، کاراکتر آغاز یا باز شدن جداکننده را مشخص می‌کند. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | کاراکتر شروع جداکننده، کاراکتر آغاز یا باز شدن جداکننده را مشخص می‌کند. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | کاراکتر جداکننده (Separator) کاراکتری را که آرگومان‌ها را در شیء جداکننده تفکیک می‌کند، مشخص می‌کند. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | کاراکتر جداکننده (Separator) کاراکتری را که آرگومان‌ها را در شیء جداکننده تفکیک می‌کند، مشخص می‌کند. |
| [getEndingCharacter()](#getEndingCharacter--) | کاراکتر پایان جداکننده، کاراکتر بسته یا پایان جداکننده را مشخص می‌کند. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | کاراکتر پایان جداکننده، کاراکتر بسته یا پایان جداکننده را مشخص می‌کند. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | رشد کاراکتر شروع، کاراکتر جداکننده و کاراکتر پایان را مشخص می‌کند. وقتی true باشد، جداکننده‌ها به صورت عمودی رشد می‌کنند تا با ارتفاع عملوند منطبق شوند. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | رشد کاراکتر شروع، کاراکتر جداکننده و کاراکتر پایان را مشخص می‌کند. وقتی true باشد، جداکننده‌ها به صورت عمودی رشد می‌کنند تا با ارتفاع عملوند منطبق شوند. |
| [getDelimiterShape()](#getDelimiterShape--) | شکل جداکننده‌ها در شیء جداکننده را مشخص می‌کند. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | شکل جداکننده‌ها در شیء جداکننده را مشخص می‌کند. |
| [delimit(char separatorCharacter)](#delimit-char-) | آرگومان‌ها را با استفاده از کاراکتر جداکننده مشخص شده جدا می‌کند. |
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

**بازگشت:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```

کاراکتر شروع جداکننده، کاراکتر آغاز یا باز شدن جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای بسته‌بندی مانند پرانتز، قلاب و کروشه هستند. مقدار پیش‌فرض: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**بازگشت:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```

کاراکتر شروع جداکننده، کاراکتر آغاز یا باز شدن جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای بسته‌بندی مانند پرانتز، قلاب و کروشه هستند. مقدار پیش‌فرض: '('.

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

کاراکتر جداکننده (Separator) کاراکتری را که آرگومان‌ها را در شیء جداکننده تفکیک می‌کند، مشخص می‌کند. مقدار پیش‌فرض: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**بازگشت:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```

کاراکتر جداکننده (Separator) کاراکتری را که آرگومان‌ها را در شیء جداکننده تفکیک می‌کند، مشخص می‌کند. مقدار پیش‌فرض: '|'.

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

کاراکتر پایان جداکننده، کاراکتر بسته یا پایان جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای بسته‌بندی مانند پرانتز، قلاب و کروشه هستند. مقدار پیش‌فرض: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**بازگشت:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```

کاراکتر پایان جداکننده، کاراکتر بسته یا پایان جداکننده را مشخص می‌کند. جداکننده‌های ریاضی کاراکترهای بسته‌بندی مانند پرانتز، قلاب و کروشه هستند. مقدار پیش‌فرض: ')'.

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

رشد کاراکتر شروع، کاراکتر جداکننده و کاراکتر پایان را مشخص می‌کند. وقتی true باشد، جداکننده‌ها به صورت عمودی رشد می‌کنند تا با ارتفاع عملوند منطبق شوند. مقدار پیش‌فرض true است

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**بازگشت:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

رشد کاراکتر شروع، کاراکتر جداکننده و کاراکتر پایان را مشخص می‌کند. وقتی true باشد، جداکننده‌ها به صورت عمودی رشد می‌کنند تا با ارتفاع عملوند منطبق شوند. مقدار پیش‌فرض true است

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

شکل جداکننده‌ها در شیء جداکننده را مشخص می‌کند. وقتی مقدار MathDelimiterShape.Centered باشد، جداکننده‌ها در اطراف محور ریاضی متن قرار می‌گیرند و همچنان می‌توانند تمام ارتفاع محتوا را پوشش دهند. وقتی مقدار MathDelimiterShape.Match باشد، ارتفاع و شکل آن‌ها دقیقاً با محتوا مطابقت می‌یابد.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**بازگشت:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```

شکل جداکننده‌ها در شیء جداکننده را مشخص می‌کند. وقتی مقدار MathDelimiterShape.Centered باشد، جداکننده‌ها در اطراف محور ریاضی متن قرار می‌گیرند و همچنان می‌توانند تمام ارتفاع محتوا را پوشش دهند. وقتی مقدار MathDelimiterShape.Match باشد، ارتفاع و شکل آن‌ها دقیقاً با محتوا مطابقت می‌یابد.

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

آرگومان‌ها را با کاراکتر جداکننده مشخص شده جداسازی می‌کند

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

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - این شیء پس از اعمال کاراکتر جداکننده