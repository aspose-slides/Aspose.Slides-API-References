---
title: IMathBox
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: بسته‌بندی منطقی جعبه‌بندی عنصر ریاضی را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/imathbox/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

جعبه‌بندی منطقی (بسته‌بندی) عنصر ریاضی را مشخص می‌کند. برای مثال، یک شیء جعبه‌بندی‌شده می‌تواند به عنوان شبیه‌ساز عملگر با یا بدون نقطه هم‌ترازی عمل کند، به عنوان نقطه شکست خط خدمت کند، یا به‌گونه‌ای گروه‌بندی شود که از شکست خط درون آن جلوگیری شود. به عنوان مثال، عملگر "==" باید جعبه‌بندی شود تا از شکست خط جلوگیری شود.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## متدها

| متد | شرح |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator Emulator. |
| [getNoBreak()](#getNoBreak--) | No break. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break. |
| [getDifferential()](#getDifferential--) | Differential. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential. |
| [getAlignmentPoint()](#getAlignmentPoint--) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
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
> ```

**بازمی‌گردد:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

شبیه‌ساز عملگر. هنگامی که مقدار true باشد، جعبه و محتویات آن به عنوان یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. این به این معنی است که، برای مثال، کاراکتر می‌تواند به عنوان نقطه‌ای برای شکست خط عمل کند و می‌تواند با سایر عملگرها هم‌ترازی شود. شبیه‌سازهای عملگر اغلب زمانی استفاده می‌شوند که یک یا چند گلیف به‌هم پیوسته یک عملگر را تشکیل دهند، مانند '=='. مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**بازمی‌گردد:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

شبیه‌ساز عملگر. هنگامی که مقدار true باشد، جعبه و محتویات آن به عنوان یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. این به این معنی است که، برای مثال، کاراکتر می‌تواند به عنوان نقطه‌ای برای شکست خط عمل کند و می‌تواند با سایر عملگرها هم‌ترازی شود. شبیه‌سازهای عملگر اغلب زمانی استفاده می‌شوند که یک یا چند گلیف به‌هم پیوسته یک عملگر را تشکیل دهند، مانند '=='. مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

بدون شکست. این ویژگی ویژگی «قابل شکست نیست» را برای جعبه شیء تعیین می‌کند. هنگامی که مقدار true باشد، هیچ شکست خطی درون جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگری که از بیش از یک عملگر باینری تشکیل شده‌اند، مهم باشد. وقتی این عنصر مشخص نشده باشد، می‌توان درون جعبه شکست خط ایجاد کرد. پیش‌فرض: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**بازمی‌گردد:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

بدون شکست. این ویژگی ویژگی «قابل شکست نیست» را برای جعبه شیء تعیین می‌کند. هنگامی که مقدار true باشد، هیچ شکست خطی درون جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگری که از بیش از یک عملگر باینری تشکیل شده‌اند، مهم باشد. وقتی این عنصر مشخص نشده باشد، می‌توان درون جعبه شکست خط ایجاد کرد. پیش‌فرض: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

مشتق. هنگامی که مقدار true باشد، جعبه به عنوان یک مشتق عمل می‌کند (به عنوان مثال، \\ud835\\udc51\\ud835\\udc65 در یک انتگرال)، و فاصله افقی مناسب برای مشتق ریاضی را دریافت می‌کند. پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**بازمی‌گردد:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

مشتق. هنگامی که مقدار true باشد، جعبه به عنوان یک مشتق عمل می‌کند (به عنوان مثال، \\ud835\\udc51\\ud835\\udc65 در یک انتگرال)، و فاصله افقی مناسب برای مشتق ریاضی را دریافت می‌کند. پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

هنگامی که مقدار true باشد، این شبیه‌ساز عملگر به عنوان نقطه هم‌ترازی عمل می‌کند؛ به این معنی که نقاط هم‌ترازی تعیین‌شده در معادلات دیگر می‌توانند با آن هم‌ترازی شوند. پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**بازمی‌گردد:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

هنگامی که مقدار true باشد، این شبیه‌ساز عملگر به عنوان نقطه هم‌ترازی عمل می‌کند؛ به این معنی که نقاط هم‌ترازی تعیین‌شده در معادلات دیگر می‌توانند با آن هم‌ترازی شوند. پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

شکست صریح مشخص می‌کند آیا در آغاز شیء Box یک شکست خط وجود دارد یا خیر، به‌طوری که خط در ابتدای شیء جعبه‌دار پیچیدگی پیدا کند. تعداد عملگر در خط قبلی متن ریاضی که باید به‌عنوان نقطه هم‌ترازی برای خط فعلی متن ریاضی استفاده شود را تعیین می‌کند؛ مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**بازمی‌گردد:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

شکست صریح مشخص می‌کند آیا در آغاز شیء Box یک شکست خط وجود دارد یا خیر، به‌طوری که خط در ابتدای شیء جعبه‌دار پیچیدگی پیدا کند. تعداد عملگر در خط قبلی متن ریاضی که باید به‌عنوان نقطه هم‌ترازی برای خط فعلی متن ریاضی استفاده شود را تعیین می‌کند؛ مقادیر ممکن: 1..255 پیش‌فرض: 0 (بدون شکست صریح)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | byte |  |