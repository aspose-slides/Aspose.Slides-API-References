---
title: MathBox
second_title: مرجع API Aspose.Slides برای جاوا
description: بسته‌بندی منطقی باکس‌گذاری عنصر ریاضی را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/mathbox/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

باکس‌گذاری منطقی (بسته‌بندی) عنصر ریاضی را مشخص می‌کند. برای مثال، یک شیء بسته‌بندی شده می‌تواند به‌عنوان شبیه‌ساز عملگر با یا بدون نقطه تراز استفاده شود، به‌عنوان نقطه شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که از ایجاد شکست خط در داخل آن جلوگیری شود. برای مثال، عملگر "==" باید بسته‌بندی شود تا از شکست خط جلوگیری شود.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | MathBox را با عنصر مشخص‌شده به عنوان آرگومان مقداردهی اولیه می‌کند |
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getOperatorEmulator()](#getOperatorEmulator--) | شبیه‌ساز عملگر. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | شبیه‌ساز عملگر. |
| [getNoBreak()](#getNoBreak--) | بدون شکست این ویژگی خصوصیت "unbreakable" را بر روی جعبه شیء مشخص می‌کند. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | بدون شکست این ویژگی خصوصیت "unbreakable" را بر روی جعبه شیء مشخص می‌کند. |
| [getDifferential()](#getDifferential--) | دیفرانسیل وقتی مقدار true باشد، جعبه به‌عنوان یک دیفرانسیل عمل می‌کند (به عنوان مثال، \\ud835\\udc51\\ud835\\udc65 در یک انتگرال)، و فاصله افقی مناسب برای دیفرانسیل ریاضی را دریافت می‌کند. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | دیفرانسیل وقتی مقدار true باشد، جعبه به‌عنوان یک دیفرانسیل عمل می‌کند (به عنوان مثال، \\ud835\\udc51\\ud835\\udc65 در یک انتگرال)، و فاصله افقی مناسب برای دیفرانسیل ریاضی را دریافت می‌کند. |
| [getAlignmentPoint()](#getAlignmentPoint--) | وقتی مقدار true باشد، این شبیه‌ساز عملگر به‌عنوان یک نقطه تراز عمل می‌کند؛ به این معنی که نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن هم‌تراز شوند. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | وقتی مقدار true باشد، این شبیه‌ساز عملگر به‌عنوان یک نقطه تراز عمل می‌کند؛ به این معنی که نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن هم‌تراز شوند. |
| [getExplicitBreak()](#getExplicitBreak--) | شکست صریح مشخص می‌کند آیا در ابتدای شیء Box یک شکست خط وجود دارد یا نه، به‌طوری که خط در ابتدای جعبه بسته شود. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | شکست صریح مشخص می‌کند آیا در ابتدای شیء Box یک شکست خط وجود دارد یا نه، به‌طوری که خط در ابتدای جعبه بسته شود. |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصوصیات کاراکتر کنترل |

### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

MathBox را با عنصر مشخص‌شده به عنوان آرگومان مقداردهی اولیه می‌کند

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصری پایه که جعبه به آن اعمال می‌شود. می‌تواند مقدار null داشته باشد. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

آرگومان پایه

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```
**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

شبیه‌ساز عملگر. وقتی مقدار true باشد، جعبه و محتویات آن مانند یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. این به این معنی است که، برای مثال، کاراکتر می‌تواند به‌عنوان نقطه‌ای برای شکست خط مورد استفاده قرار گیرد و می‌تواند با سایر عملگرها هم‌تراز شود. شبیه‌سازهای عملگر معمولاً زمانی استفاده می‌شوند که یک یا چند گلیف برای تشکیل یک عملگر ترکیب شوند، مانند '=='. مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**بازگشت:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

شبیه‌ساز عملگر. وقتی مقدار true باشد، جعبه و محتویات آن مانند یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. این به این معنی است که، برای مثال، کاراکتر می‌تواند به‌عنوان نقطه‌ای برای شکست خط مورد استفاده قرار گیرد و می‌تواند با سایر عملگرها هم‌تراز شود. شبیه‌سازهای عملگر معمولاً زمانی استفاده می‌شوند که یک یا چند گلیف برای تشکیل یک عملگر ترکیب شوند، مانند '=='. مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

بدون شکست این ویژگی خصوصیت "unbreakable" را بر روی جعبه شیء مشخص می‌کند. وقتی مقدار true باشد، هیچ شکست خطی در داخل جعبه امکان‌پذیر نیست. این می‌تواند برای شبیه‌سازهای عملگری که از بیش از یک عملگر دودویی تشکیل شده‌اند مهم باشد. زمانی که این عنصر مشخص نشود، امکان وقوع شکست خط داخل جعبه وجود دارد. مقدار پیش‌فرض: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```
**بازگشت:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

بدون شکست این ویژگی خصوصیت "unbreakable" را بر روی جعبه شیء مشخص می‌کند. وقتی مقدار true باشد، هیچ شکست خطی در داخل جعبه امکان‌پذیر نیست. این می‌تواند برای شبیه‌سازهای عملگری که از بیش از یک عملگر دودویی تشکیل شده‌اند مهم باشد. زمانی که این عنصر مشخص نشود، امکان وقوع شکست خط داخل جعبه وجود دارد. مقدار پیش‌فرض: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

دیفرانسیل وقتی مقدار true باشد، جعبه به‌عنوان یک دیفرانسیل عمل می‌کند (به عنوان مثال، \\ud835\\udc51\\ud835\\udc65 در یک انتگرال)، و فاصله افقی مناسب برای دیفرانسیل ریاضی را دریافت می‌کند. مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```
**بازگشت:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```

دیفرانسیل وقتی مقدار true باشد، جعبه به‌عنوان یک دیفرانسیل عمل می‌کند (به عنوان مثال، \\ud835\\udc51\\ud835\\udc65 در یک انتگرال)، و فاصله افقی مناسب برای دیفرانسیل ریاضی را دریافت می‌کند. مقدار پیش‌فرض: false

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
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```

وقتی مقدار true باشد، این شبیه‌ساز عملگر به‌عنوان یک نقطه تراز عمل می‌کند؛ به این معنی که نقاط تراز تعیین‌شده در سایر معادلات می‌توانند با آن هم‌تراز شوند. مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```
**بازگشت:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```

وقتی مقدار true باشد، این شبیه‌ساز عملگر به‌عنوان یک نقطه تراز عمل می‌کند؛ به این معنی که نقاط تراز تعیین‌شده در سایر معادلات می‌توانند با آن هم‌تراز شوند. مقدار پیش‌فرض: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```

شکست صریح مشخص می‌کند آیا در ابتدای شیء Box یک شکست خط وجود دارد یا نه، به‌طوری که خط در ابتدای جعبه بسته شود. شماره‌ عملگر در خط قبلی متن ریاضی را که به عنوان نقطه تراز برای خط فعلی متن ریاضی استفاده شود مشخص می‌کند. مقادیر ممکن: 1..255 مقدار پیش‌فرض: 0 (بدون شکست صریح)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```
**بازگشت:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```

شکست صریح مشخص می‌کند آیا در ابتدای شیء Box یک شکست خط وجود دارد یا نه، به‌طوری که خط در ابتدای جعبه بسته شود. شماره‌ عملگر در خط قبلی متن ریاضی را که به عنوان نقطه تراز برای خط فعلی متن ریاضی استفاده شود مشخص می‌کند. مقادیر ممکن: 1..255 مقدار پیش‌فرض: 0 (بدون شکست صریح)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

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

خصوصیات کاراکتر کنترل

**بازگشت:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps