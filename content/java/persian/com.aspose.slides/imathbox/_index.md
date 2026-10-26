---
title: IMathBox
second_title: مرجع API Aspose.Slides برای Java
description: پکیج‌بندی منطقی جعبه‌ای عنصر ریاضی را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/imathbox/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

مشخص می‌کند که بسته‌بندی منطقی (پیشه) عنصر ریاضی چگونه است. برای مثال، یک شیء بسته‌بندی شده می‌تواند به عنوان یک شبیه‌ساز عملگر با یا بدون نقطهٔ تراز استفاده شود، می‌تواند به عنوان نقطهٔ شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که از ایجاد شکست خط درون آن جلوگیری شود. برای نمونه، عملگر «==» باید بسته‌بندی شود تا از شکست خط جلوگیری گردد.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getOperatorEmulator()](#getOperatorEmulator--) | شبیه‌ساز عملگر. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | شبیه‌ساز عملگر. |
| [getNoBreak()](#getNoBreak--) | بدون شکست. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | بدون شکست. |
| [getDifferential()](#getDifferential--) | دیفرانسیل. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | دیفرانسیل. |
| [getAlignmentPoint()](#getAlignmentPoint--) | وقتی true باشد، این شبیه‌ساز عملگر به‌عنوان نقطهٔ تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن تراز شوند. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | وقتی true باشد، این شبیه‌ساز عملگر به‌عنوان نقطهٔ تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن تراز شوند. |
| [getExplicitBreak()](#getExplicitBreak--) | شکست صریح تعیین می‌کند که آیا در شروع شیء Box یک شکست خط وجود دارد یا نه، به‌طوری که خط در شروع شیء box پیچ‌ویژه شود. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | شکست صریح تعیین می‌کند که آیا در شروع شیء Box یک شکست خط وجود دارد یا نه، به‌طوری که خط در شروع شیء box پیچ‌ویژه شود. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

آرگومان پایه

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
>  ```


**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

شبیه‌ساز عملگر. وقتی true باشد، جعبه و محتویات آن به‌عنوان یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. به عنوان مثال، این کاراکتر می‌تواند به‌عنوان نقطهٔ شکست خط استفاده شود و قابل تراز با عملگرهای دیگر باشد. شبیه‌سازهای عملگر معمولاً هنگامی استفاده می‌شوند که یک یا چند گلیف برای تشکیل یک عملگر ترکیب می‌شوند، مانند «==». مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Returns:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

شبیه‌ساز عملگر. وقتی true باشد، جعبه و محتویات آن به‌عنوان یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. به عنوان مثال، این کاراکتر می‌تواند به‌عنوان نقطهٔ شکست خط استفاده شود و قابل تراز با عملگرهای دیگر باشد. شبیه‌سازهای عملگر معمولاً هنگامی استفاده می‌شوند که یک یا چند گلیف برای تشکیل یک عملگر ترکیب می‌شوند، مانند «==». مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

بدون شکست. این ویژگی ویژگی «قابل شکستن نیست» را بر روی جعبهٔ شیء مشخص می‌کند. وقتی true باشد، هیچ شکستی درون جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگر که شامل بیش از یک عملگر دودویی هستند مهم باشد. وقتی این عنصر مشخص نشود، شکسته‌ها می‌توانند درون جعبه رخ دهند. مقدار پیش‌فرض: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Returns:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

بدون شکست. این ویژگی ویژگی «قابل شکستن نیست» را بر روی جعبهٔ شیء مشخص می‌کند. وقتی true باشد، هیچ شکستی درون جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگر که شامل بیش از یک عملگر دودویی هستند مهم باشد. وقتی این عنصر مشخص نشود، شکسته‌ها می‌توانند درون جعبه رخ دهند. مقدار پیش‌فرض: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

دیفرانسیل. وقتی true باشد، جعبه به‌عنوان یک دیفرانسیل عمل می‌کند (مثلاً \\ud835\\udc51\\ud835\\udc65 در یک انتگرال)، و فاصلهٔ افقی مناسب برای دیفرانسیل ریاضی را دریافت می‌کند. مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Returns:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

دیفرانسیل. وقتی true باشد، جعبه به‌عنوان یک دیفرانسیل عمل می‌کند (مثلاً \\ud835\\udc51\\ud835\\udc65 در یک انتگرال)، و فاصلهٔ افقی مناسب برای دیفرانسیل ریاضی را دریافت می‌کند. مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

وقتی true باشد، این شبیه‌ساز عملگر به‌عنوان نقطهٔ تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن تراز شوند. مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Returns:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

وقتی true باشد، این شبیه‌ساز عملگر به‌عنوان نقطهٔ تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن تراز شوند. مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

شکست صریح تعیین می‌کند که آیا در شروع شیء Box یک شکست خط وجود دارد یا نه، به‌طوری که خط در شروع شیء box پیچ‌ویژه شود. عدد عملگر در خط قبلی متن ریاضی که باید به‌عنوان نقطهٔ تراز برای خط فعلی متن ریاضی استفاده شود را مشخص می‌کند؛ مقادیر ممکن: 1..255 مقدار پیش‌فرض: 0 (بدون شکست صریح)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Returns:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

شکست صریح تعیین می‌کند که آیا در شروع شیء Box یک شکست خط وجود دارد یا نه، به‌طوری که خط در شروع شیء box پیچ‌ویژه شود. عدد عملگر در خط قبلی متن ریاضی که باید به‌عنوان نقطهٔ تراز برای خط فعلی متن ریاضی استفاده شود را مشخص می‌کند؛ مقادیر ممکن: 1..255 مقدار پیش‌فرض: 0 (بدون شکست صریح)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |