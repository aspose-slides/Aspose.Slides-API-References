---
title: MathBox
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: بسته‌بندی منطقی جعبه‌سازی عنصر ریاضی را تعیین می‌کند.
type: docs
url: /fa/com.aspose.slides/mathbox/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

منطق جعبه‌بندی (بسته‌بندی) عنصر ریاضی را مشخص می‌کند. به عنوان مثال، یک شیء جعبه‌شده می‌تواند به عنوان شبیه‌ساز عملگر با یا بدون نقطه‌ی تراز عمل کند، به عنوان نقطه‌ی شکست خط عمل کند، یا به‌گونه‌ای گروه‌بندی شود که از شکست خط درون آن جلوگیری شود. برای مثال، عملگر "==" باید جعبه‌شود تا از شکست خط جلوگیری شود.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## سازندگان

| سازنده | توضیح |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | MathBox را با عنصری که به‌عنوان آرگومان مشخص شده، مقداردهی اولیه می‌کند |
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getOperatorEmulator()](#getOperatorEmulator--) | شبیه‌ساز عملگر. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | شبیه‌ساز عملگر. |
| [getNoBreak()](#getNoBreak--) | بدون شکست این ویژگی خاصیت "unbreakable" را بر روی جعبهٔ شیء مشخص می‌کند. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | بدون شکست این ویژگی خاصیت "unbreakable" را بر روی جعبهٔ شیء مشخص می‌کند. |
| [getDifferential()](#getDifferential--) | تفاضلی وقتی true باشد، جعبه به‌عنوان یک تفاضل عمل می‌کند (مثلاً \\ud835\\udc51\\ud835\\udc65 در یک انتگرال‌گیر)، و فواصل افقی مناسب برای تفاضل ریاضی را دریافت می‌کند. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | تفاضلی وقتی true باشد، جعبه به‌عنوان یک تفاضل عمل می‌کند (مثلاً \\ud835\\udc51\\ud835\\udc65 در یک انتگرال‌گیر)، و فواصل افقی مناسب برای تفاضل ریاضی را دریافت می‌کند. |
| [getAlignmentPoint()](#getAlignmentPoint--) | وقتی true باشد، این شبیه‌ساز عملگر به‌عنوان نقطه‌ی تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن هم‌تراز شوند. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | وقتی true باشد، این شبیه‌ساز عملگر به‌عنوان نقطه‌ی تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن هم‌تراز شوند. |
| [getExplicitBreak()](#getExplicitBreak--) | شکست صریح مشخص می‌کند آیا خطی در ابتدای شیء Box وجود دارد که باعث پیچش خط در ابتدای شیء جعبه شود یا خیر. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | شکست صریح مشخص می‌کند آیا خطی در ابتدای شیء Box وجود دارد که باعث پیچش خط در ابتدای شیء جعبه شود یا خیر. |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکتر کنترل |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```


MathBox را با عنصری که به‌عنوان آرگومان مشخص شده، مقداردهی اولیه می‌کند

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصری پایه که جعبه به آن اعمال می‌شود. می‌تواند null باشد. |

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


شبیه‌ساز عملگر. وقتی true باشد، جعبه و محتوای آن مانند یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. این به این معنی است که، به عنوان مثال، کاراکتر می‌تواند به‌عنوان نقطه‌ای برای شکست خط عمل کند و به سایر عملگرها هم‌تراز شود. شبیه‌سازهای عملگر اغلب زمانی استفاده می‌شوند که یک یا چند گلیف برای تشکیل یک عملگر ترکیب شوند، مانند '=='. مقدار پیش‌فرض: false

--------------------

> ```
> مثال:
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


شبیه‌ساز عملگر. وقتی true باشد، جعبه و محتوای آن مانند یک عملگر واحد رفتار می‌کنند و ویژگی‌های یک عملگر را به ارث می‌برند. این به این معنی است که، به عنوان مثال، کاراکتر می‌تواند به‌عنوان نقطه‌ای برای شکست خط عمل کند و به سایر عملگرها هم‌تراز شود. شبیه‌سازهای عملگر اغلب زمانی استفاده می‌شوند که یک یا چند گلیف برای تشکیل یک عملگر ترکیب شوند، مانند '=='. مقدار پیش‌فرض: false

--------------------

> ```
> مثال:
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


بدون شکست این ویژگی خاصیت "unbreakable" را بر روی جعبهٔ شیء مشخص می‌کند. وقتی true باشد، هیچ شکست خطی درون جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگر که بیش از یک عملگر باینری تشکیل می‌دهند مهم باشد. وقتی این عنصر مشخص نشود، می‌توان درون جعبه شکست‌ها را رخ داد. مقدار پیش‌فرض: true

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


بدون شکست این ویژگی خاصیت "unbreakable" را بر روی جعبهٔ شیء مشخص می‌کند. وقتی true باشد، هیچ شکست خطی درون جعبه رخ نمی‌دهد. این می‌تواند برای شبیه‌سازهای عملگر که بیش از یک عملگر باینری تشکیل می‌دهند مهم باشد. وقتی این عنصر مشخص نشود، می‌توان درون جعبه شکست‌ها را رخ داد. مقدار پیش‌فرض: true

--------------------

> ```
> مثال:
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


تفاضلی وقتی true باشد، جعبه به‌عنوان یک تفاضل عمل می‌کند (مثلاً \\ud835\\udc51\\ud835\\udc65 در یک انتگرال‌گیر)، و فواصل افقی مناسب برای تفاضل ریاضی را دریافت می‌کند. مقدار پیش‌فرض: false

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


تفاضلی وقتی true باشد، جعبه به‌عنوان یک تفاضل عمل می‌کند (مثلاً \\ud835\\udc51\\ud835\\udc65 در یک انتگرال‌گیر)، و فواصل افقی مناسب برای تفاضل ریاضی را دریافت می‌کند. مقدار پیش‌فرض: false

--------------------

> ```
> مثال:
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


وقتی true باشد، این شبیه‌ساز عملگر به‌عنوان نقطه‌ی تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن هم‌تراز شوند. مقدار پیش‌فرض: false

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


وقتی true باشد، این شبیه‌ساز عملگر به‌عنوان نقطه‌ی تراز عمل می‌کند؛ یعنی نقاط تراز تعیین‌شده در معادلات دیگر می‌توانند با آن هم‌تراز شوند. مقدار پیش‌فرض: false

--------------------

> ```
> مثال:
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


شکست صریح مشخص می‌کند آیا در ابتدای شیء Box یک شکست خط وجود دارد که باعث پیچش خط در ابتدای شیء جعبه شود یا خیر. عدد عملگر در خط قبلی متن ریاضی که باید به‌عنوان نقطه تراز برای خط جاری متن ریاضی استفاده شود را تعیین می‌کند. مقادیر ممکن: 1..255 مقدار پیش‌فرض: 0 (بدون شکست صریح)

--------------------

> ```
> مثال:
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


شکست صریح مشخص می‌کند آیا در ابتدای شیء Box یک شکست خط وجود دارد که باعث پیچش خط در ابتدای شیء جعبه شود یا خیر. عدد عملگر در خط قبلی متن ریاضی که باید به‌عنوان نقطه تراز برای خط جاری متن ریاضی استفاده شود را تعیین می‌کند. مقادیر ممکن: 1..255 مقدار پیش‌فرض: 0 (بدون شکست صریح)

--------------------

> ```
> مثال:
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


ویژگی‌های کاراکتر کنترل

**بازگشت:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps