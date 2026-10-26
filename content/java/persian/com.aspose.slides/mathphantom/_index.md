---
title: MathPhantom
second_title: مرجع API Aspose.Slides برای جاوا
description: یک شی ریاضی فانتوم ltmphantgt را نشان می‌دهد که طرح‌بندی عنصر فرزند خود را تحت تأثیر قرار می‌دهد بدون این‌که لزوماً آن را نمایش دهد.
type: docs
url: /fa/com.aspose.slides/mathphantom/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

یک شی ریاضی فانتوم (<m:phant>) را نشان می‌دهد که طرح‌بندی عنصر فرزند خود را تحت تأثیر قرار می‌دهد بدون این‌که لزوماً آن را نمایش دهد. یک فانتوم می‌تواند عبارت پایه خود را مخفی کند در حالی که عرض، ارتفاع یا عمق آن را برای تراز فرمول‌ها یا رزرو فضا حفظ می‌کند. رفتار قابل‌مشاهده و هندسی توسط ویژگی‌هایی مانند Show، ZeroWid، ZeroAsc، ZeroDesc و Transp کنترل می‌شود.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // مخفی کردن محتوا
>  phantom.setZeroWidth(false);     // نگه داشتن عرض
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس [MathPhantom](../../com.aspose.slides/mathphantom) را با استفاده از عنصر ریاضی پایه مشخص‌شده مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getShow()](#getShow--) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود. |
| [setShow(boolean value)](#setShow-boolean-) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود. |
| [getZeroWidth()](#getZeroWidth--) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عرض عنصر پایه باید به‌عنوان صفر درنظر گرفته شود. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عرض عنصر پایه باید به‌عنوان صفر درنظر گرفته شود. |
| [getZeroAsc()](#getZeroAsc--) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا صعود (ارتفاع بالای خط پایه) عنصر پایه باید به‌عنوان صفر درنظر گرفته شود. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا صعود (ارتفاع بالای خط پایه) عنصر پایه باید به‌عنوان صفر درنظر گرفته شود. |
| [getZeroDesc()](#getZeroDesc--) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا نزول (عمق زیر خط پایه) عنصر پایه باید به‌عنوان صفر درنظر گرفته شود. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا نزول (عمق زیر خط پایه) عنصر پایه باید به‌عنوان صفر درنظر گرفته شود. |
| [getTransp()](#getTransp--) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف است. |
| [setTransp(boolean value)](#setTransp-boolean-) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف است. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکتر کنترل |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

یک نمونه جدید از کلاس [MathPhantom](../../com.aspose.slides/mathphantom) را با استفاده از عنصر ریاضی پایه مشخص‌شده مقداردهی اولیه می‌کند.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر پایه [IMathElement](../../com.aspose.slides/imathelement) که قابل مشاهده و طرح‌بندی آن توسط فانتوم کنترل می‌شود. این عنصر محتوایی را تعریف می‌کند که ممکن است مخفی یا نشان داده شود، در حالی که همچنان بر تراز هندسی ریاضیات اطراف تأثیر می‌گذارد. |

--------------------

عنصر فانتوم برای رزرو یا حذف فضای بصری عبارت پایه خود بدون این‌که لزوماً نمایش داده شود، استفاده می‌شود. این عنصر متناظر با عنصر OMML <m:phant> است. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

آرگومان پایه

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود.

--------------------

هنگامی که مقدار false باشد، عنصر پایه مخفی می‌شود اما ممکن است بسته به تنظیمات دیگر فانتوم همچنان فضا را اشغال کند. متناظر با ویژگی OMML m:show.

**بازگشت:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود.

--------------------

هنگامی که مقدار false باشد، عنصر پایه مخفی می‌شود اما ممکن است بسته به تنظیمات دیگر فانتوم همچنان فضا را اشغال کند. متناظر با ویژگی OMML m:show.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عرض عنصر پایه باید به‌عنوان صفر درنظر گرفته شود.

--------------------

هنگامی که مقدار true باشد، فانتوم برای عنصر پایه خود فضای افقی رزرو نمی‌کند. متناظر با ویژگی OMML m:zeroWid.

**بازگشت:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عرض عنصر پایه باید به‌عنوان صفر درنظر گرفته شود.

--------------------

هنگامی که مقدار true باشد، فانتوم برای عنصر پایه خود فضای افقی رزرو نمی‌کند. متناظر با ویژگی OMML m:zeroWid.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا صعود (ارتفاع بالای خط پایه) عنصر پایه باید به‌عنوان صفر درنظر گرفته شود.

--------------------

هنگامی که مقدار true باشد، فانتوم خط پایه خط ریاضی اطراف را بالا نمی‌برد. متناظر با ویژگی OMML m:zeroAsc.

**بازگشت:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا صعود (ارتفاع بالای خط پایه) عنصر پایه باید به‌عنوان صفر درنظر گرفته شود.

--------------------

هنگامی که مقدار true باشد، فانتوم خط پایه خط ریاضی اطراف را بالا نمی‌برد. متناظر با ویژگی OMML m:zeroAsc.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا نزول (عمق زیر خط پایه) عنصر پایه باید به‌عنوان صفر درنظر گرفته شود.

--------------------

هنگامی که مقدار true باشد، فانتوم خط پایه خط ریاضی اطراف را پایین نمی‌آورد. متناظر با ویژگی OMML m:zeroDesc.

**بازگشت:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا نزول (عمق زیر خط پایه) عنصر پایه باید به‌عنوان صفر درنظر گرفته شود.

--------------------

هنگامی که مقدار true باشد، فانتوم خط پایه خط ریاضی اطراف را پایین نمی‌آورد. متناظر با ویژگی OMML m:zeroDesc.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف است.

--------------------

هنگامی که مقدار true باشد، عملگرها و نمادهای داخل فانتوم همچنان بر فاصله‌گذاری ریاضی اطراف تأثیر می‌گذارند (گویی قابل مشاهده‌اند). هنگامی که مقدار false باشد، قوانین فاصله‌گذاری مبتنی بر کلاس نادیده گرفته می‌شود. متناظر با ویژگی OMML m:transp.

**بازگشت:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف است.

--------------------

هنگامی که مقدار true باشد، عملگرها و نمادهای داخل فانتوم همچنان بر فاصله‌گذاری ریاضی اطراف تأثیر می‌گذارند (گویی قابل مشاهده‌اند). هنگامی که مقدار false باشد، قوانین فاصله‌گذاری مبتنی بر کلاس نادیده گرفته می‌شود. متناظر با ویژگی OMML m:transp.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

ویژگی‌های کاراکتر کنترل

**بازگشت:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

دریافت عناصر فرزند

**بازگشت:**
com.aspose.slides.IMathElement[]