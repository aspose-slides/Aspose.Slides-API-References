---
title: MathDelimiter
second_title: Aspose.Slides برای مرجع API جاوا
description: شی delimiter را که شامل کاراکترهای باز و بسته مانند پرانتزها، آکولادها، کروشه‌ها و نوارهای عمودی است و یک یا چند عنصر ریاضی داخل آن توسط کاراکتر مشخصی جدا می‌شوند، مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/mathdelimiter/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

شی محدد را مشخص می‌کند که شامل کاراکترهای باز و بسته (مانند پرانتزها، آکولادها، کروشه‌ها و نوارهای عمودی) است و یک یا چند عنصر ریاضی داخل آن، با کاراکتر مشخصی جدا شده‌اند. مثال‌ها: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | MathDelimiter را با عنصری که به عنوان آرگومان پایه تک مشخص می‌شود، مقداردهی اولیه می‌کند |
## متدها

| متد | توضیح |
| --- | --- |
| [getArguments()](#getArguments--) | یک یا چند عنصر ریاضی که با کاراکترهای محدد جدا شده‌اند |
| [getBeginningCharacter()](#getBeginningCharacter--) | کاراکتر شروع محدد را مشخص می‌کند، یعنی کاراکتر آغازگر. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | کاراکتر شروع محدد را مشخص می‌کند، یعنی کاراکتر آغازگر. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | کاراکتر جداکننده محدد را مشخص می‌کند، یعنی کاراکتری که آرگومان‌ها را در شی محدد جدا می‌کند. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | کاراکتر جداکننده محدد را مشخص می‌کند، یعنی کاراکتری که آرگومان‌ها را در شی محدد جدا می‌کند. |
| [getEndingCharacter()](#getEndingCharacter--) | کاراکتر پایان محدد را مشخص می‌کند، یعنی کاراکتر خاتمه‌دهنده. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | کاراکتر پایان محدد را مشخص می‌کند، یعنی کاراکتر خاتمه‌دهنده. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | رشد کاراکترهای شروع، جداکننده و پایان را مشخص می‌کند؛ هنگامی که true باشد، محددها به صورت عمودی برای مطابقت با ارتفاع عملوند رشد می‌کنند. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | رشد کاراکترهای شروع، جداکننده و پایان را مشخص می‌کند؛ هنگامی که true باشد، محددها به صورت عمودی برای مطابقت با ارتفاع عملوند رشد می‌کنند. |
| [getDelimiterShape()](#getDelimiterShape--) | شکل محددها در شی محدد را مشخص می‌کند. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | شکل محددها در شی محدد را مشخص می‌کند. |
| [delimit(char separatorCharacter)](#delimit-char-) | آرگومان‌ها را با کاراکتر محدد مشخص‌شده جدا می‌کند |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | یک عنصر ریاضی را در کاراکترهای مشخصی مانند پرانتز یا سایر کاراکترها به‌عنوان قاب می‌گیرد |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکتر کنترل |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```


MathDelimiter را با عنصری که به عنوان آرگومان پایه تک مشخص می‌شود، مقداردهی اولیه می‌کند

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر پایه‌ای که محدد به آن اعمال می‌شود. می‌تواند null باشد. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


یک یا چند عنصر ریاضی که با کاراکترهای محدد جدا شده‌اند

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
public final char getBeginningCharacter()
```


کاراکتر شروع محدد را مشخص می‌کند، یعنی کاراکتر آغازگر. محددهای ریاضی کاراکترهای محصورکننده‌ای مانند پرانتزها، کروشه‌ها و آکولادها هستند. مقدار پیش‌فرض: '('.

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
public final void setBeginningCharacter(char value)
```


کاراکتر شروع محدد را مشخص می‌کند، یعنی کاراکتر آغازگر. محددهای ریاضی کاراکترهای محصورکننده‌ای مانند پرانتزها، کروشه‌ها و آکولادها هستند. مقدار پیش‌فرض: '('.

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
public final char getSeparatorCharacter()
```


کاراکتر جداکننده محدد را مشخص می‌کند، یعنی کاراکتری که آرگومان‌ها را در شی محدد جدا می‌کند. مقدار پیش‌فرض: '|'.

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
public final void setSeparatorCharacter(char value)
```


کاراکتر جداکننده محدد را مشخص می‌کند، یعنی کاراکتری که آرگومان‌ها را در شی محدد جدا می‌کند. مقدار پیش‌فرض: '|'.

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
public final char getEndingCharacter()
```


کاراکتر پایان محدد را مشخص می‌کند، یعنی کاراکتر خاتمه‌دهنده. محددهای ریاضی کاراکترهای محصورکننده‌ای مانند پرانتزها، کروشه‌ها و آکولادها هستند. مقدار پیش‌فرض: ')'.

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
public final void setEndingCharacter(char value)
```


کاراکتر پایان محدد را مشخص می‌کند، یعنی کاراکتر خاتمه‌دهنده. محددهای ریاضی کاراکترهای محصورکننده‌ای مانند پرانتزها، کروشه‌ها و آکولادها هستند. مقدار پیش‌فرض: ')'.

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
public final boolean getGrowToMatchOperandHeight()
```


رشد کاراکترهای شروع، جداکننده و پایان را مشخص می‌کند؛ هنگامی که true باشد، محددها به صورت عمودی برای مطابقت با ارتفاع عملوند رشد می‌کنند. مقدار پیش‌فرض true است

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
public final void setGrowToMatchOperandHeight(boolean value)
```


رشد کاراکترهای شروع، جداکننده و پایان را مشخص می‌کند؛ هنگامی که true باشد، محددها به صورت عمودی برای مطابقت با ارتفاع عملوند رشد می‌کنند. مقدار پیش‌فرض true است

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
public final int getDelimiterShape()
```


شکل محددها در شی محدد را مشخص می‌کند. وقتی مقدار MathDelimiterShape.Centered باشد، محددها حول محور ریاضی متن ریاضی متمرکز می‌شوند و همچنان می‌توانند ارتفاع محتوای خود را تطبیق دهند. وقتی مقدار MathDelimiterShape.Match باشد، ارتفاع و شکل آن‌ها دقیقاً با محتوایشان تطبیق می‌یابد.

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
public final void setDelimiterShape(int value)
```


شکل محددها در شی محدد را مشخص می‌کند. وقتی مقدار MathDelimiterShape.Centered باشد، محددها حول محور ریاضی متن ریاضی متمرکز می‌شوند و همچنان می‌توانند ارتفاع محتوای خود را تطبیق دهند. وقتی مقدار MathDelimiterShape.Match باشد، ارتفاع و شکل آن‌ها دقیقاً با محتوایشان تطبیق می‌یابد.

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
public final IMathDelimiter delimit(char separatorCharacter)
```


آرگومان‌ها را با کاراکتر محدد مشخص‌شده جدا می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separatorCharacter | char | کاراکتر محدد |

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - این شی پس از اعمال کاراکتر محدد

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


یک عنصر ریاضی را در کاراکترهای مشخصی مانند پرانتز یا سایر کاراکترها به‌عنوان قاب می‌گیرد

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char | کاراکتر آغاز (معمولاً پرانتز چپ) |
| endingCharacter | char | کاراکتر پایان (معمولاً پرانتز راست) |

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - اگر beginningCharacter و endingCharacter null باشند، فقط ویژگی‌های مربوطه مقداردهی می‌شوند و شی جدیدی ایجاد نمی‌شود (این نمونه برگردانده می‌شود). در غیر این صورت، عنصر ریاضی جدیدی از نوع Delimiter که شامل کاراکترهای مشخص‌شده به‌عنوان قاب است و این نمونهٔ [MathDelimiter](../../com.aspose.slides/mathdelimiter) داخل آن قاب شده است، برگردانده می‌شود.

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


دریافت عناصر فرزند

**بازگشت:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


ویژگی‌های کاراکتر کنترل

**بازگشت:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps