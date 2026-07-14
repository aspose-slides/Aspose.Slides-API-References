---
title: MathPhantom
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک شیء ریاضی فانتوم ltmphantgt را نشان می‌دهد که چیدمان عنصر فرزند خود را تحت تأثیر قرار می‌دهد بدون این‌که لزوماً آن را نمایش دهد.
type: docs
url: /fa/com.aspose.slides/mathphantom/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

نمایش یک شیء ریاضی فانتوم (<m:phant>) که چیدمان عنصر فرزند خود را تحت تأثیر قرار می‌دهد بدون این‌که لزوماً آن را نمایش دهد. یک فانتوم می‌تواند عبارت پایه خود را مخفی کند در حالی که عرض، ارتفاع یا عمق آن را حفظ می‌کند تا فرمول‌ها را هم‌تراز یا فضا را رزرو کند. رفتار دید و هندسه توسط ویژگی‌هایی مانند Show، ZeroWid، ZeroAsc، ZeroDesc و Transp کنترل می‌شود.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // مخفی کردن محتوا
>  phantom.setZeroWidth(false);     // حفظ عرض
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس [MathPhantom](../../com.aspose.slides/mathphantom) را با استفاده از عنصر ریاضی پایه مشخص شده مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getShow()](#getShow--) | مقداری را که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود دریافت یا تنظیم می‌کند. |
| [setShow(boolean value)](#setShow-boolean-) | مقداری را که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود دریافت یا تنظیم می‌کند. |
| [getZeroWidth()](#getZeroWidth--) | مقداری را که نشان می‌دهد آیا عرض عنصر پایه باید به عنوان صفر در نظر گرفته شود دریافت یا تنظیم می‌کند. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | مقداری را که نشان می‌دهد آیا عرض عنصر پایه باید به عنوان صفر در نظر گرفته شود دریافت یا تنظیم می‌کند. |
| [getZeroAsc()](#getZeroAsc--) | مقداری را که نشان می‌دهد آیا ارتفاع (ارتفاع بالای خط پایه) عنصر پایه باید به عنوان صفر در نظر گرفته شود دریافت یا تنظیم می‌کند. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | مقداری را که نشان می‌دهد آیا ارتفاع (ارتفاع بالای خط پایه) عنصر پایه باید به عنوان صفر در نظر گرفته شود دریافت یا تنظیم می‌کند. |
| [getZeroDesc()](#getZeroDesc--) | مقداری را که نشان می‌دهد آیا عمق (عمق زیر خط پایه) عنصر پایه باید به عنوان صفر در نظر گرفته شود دریافت یا تنظیم می‌کند. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | مقداری را که نشان می‌دهد آیا عمق (عمق زیر خط پایه) عنصر پایه باید به عنوان صفر در نظر گرفته شود دریافت یا تنظیم می‌کند. |
| [getTransp()](#getTransp--) | مقداری را که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف است دریافت یا تنظیم می‌کند. |
| [setTransp(boolean value)](#setTransp-boolean-) | مقداری را که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف است دریافت یا تنظیم می‌کند. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکتر کنترلی |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

یک نمونه جدید از کلاس [MathPhantom](../../com.aspose.slides/mathphantom) را با استفاده از عنصر ریاضی پایه مشخص شده مقداردهی اولیه می‌کند.

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر پایه [IMathElement](../../com.aspose.slides/imathelement) که نمایش و چیدمان آن توسط فانتوم کنترل می‌شود. این عنصر محتوایی را تعریف می‌کند که ممکن است مخفی یا نشان داده شود، در حالی که همچنان بر تراز هندسی ریاضیات اطراف تاثیر می‌گذارد. |

--------------------

عنصر فانتوم برای رزرو یا حذف فضای بصری عبارت پایه خود بدون لزوماً نمایش آن استفاده می‌شود. این عنصر با عنصر OMML <m:phant> مطابقت دارد. |

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

مقداری را که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود دریافت یا تنظیم می‌کند.

--------------------

هنگامی که مقدار false باشد، عنصر پایه مخفی می‌شود اما ممکن است بسته به تنظیمات دیگر فانتوم همچنان فضا اشغال کند. متناظر با ویژگی OMML m:show.

**بازگشت:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

مقداری را که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود دریافت یا تنظیم می‌کند.

--------------------

هنگامی که مقدار false باشد، عنصر پایه مخفی می‌شود اما ممکن است بسته به تنظیمات دیگر فانتوم همچنان فضا اشغال کند. متناظر با ویژگی OMML m:show.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

مقداری را که نشان می‌دهد آیا عرض عنصر پایه باید به عنوان صفر در نظر گرفته شود دریافت یا تنظیم می‌کند.

--------------------

هنگامی که مقدار true باشد، فانتوم فضای افقی برای پایه‌اش رزرو نمی‌کند. متناظر با ویژگی OMML m:zeroWid.

**بازگشت:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

مقداری را که نشان می‌دهد آیا عرض عنصر پایه باید به عنوان صفر در نظر گرفته شود دریافت یا تنظیم می‌کند.

--------------------

هنگامی که مقدار true باشد، فانتوم فضای افقی برای پایه‌اش رزرو نمی‌کند. متناظر با ویژگی OMML m:zeroWid.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

مقداری را که نشان می‌دهد آیا ارتفاع (ارتفاع بالای خط پایه) عنصر پایه باید به عنوان صفر در نظر گرفته شود دریافت یا تنظیم می‌کند.

--------------------

هنگامی که مقدار true باشد، فانتوم خط پایه خط ریاضی اطراف را بالا نمی‌برد. متناظر با ویژگی OMML m:zeroAsc.

**بازگشت:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

مقداری را که نشان می‌دهد آیا ارتفاع (ارتفاع بالای خط پایه) عنصر پایه باید به عنوان صفر در نظر گرفته شود دریافت یا تنظیم می‌کند.

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

مقداری را که نشان می‌دهد آیا عمق (عمق زیر خط پایه) عنصر پایه باید به عنوان صفر در نظر گرفته شود دریافت یا تنظیم می‌کند.

--------------------

هنگامی که مقدار true باشد، فانتوم خط پایه خط ریاضی اطراف را پایین نمی‌آورد. متناظر با ویژگی OMML m:zeroDesc.

**بازگشت:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

مقداری را که نشان می‌دهد آیا عمق (عمق زیر خط پایه) عنصر پایه باید به عنوان صفر در نظر گرفته شود دریافت یا تنظیم می‌کند.

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

مقداری را که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف است دریافت یا تنظیم می‌کند.

--------------------

هنگامی که مقدار true باشد، عملگرها و نمادهای داخل فانتوم همچنان بر فاصله‌گذاری ریاضی اطراف فانتوم تأثیر می‌گذارند (گویی قابل مشاهده هستند). هنگامی که مقدار false باشد، قوانین فاصله‌گذاری مبتنی بر کلاس نادیده گرفته می‌شود. متناظر با ویژگی OMML m:transp.

**بازگشت:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

مقداری را که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف است دریافت یا تنظیم می‌کند.

--------------------

هنگامی که مقدار true باشد، عملگرها و نمادهای داخل فانتوم همچنان بر فاصله‌گذاری ریاضی اطراف فانتوم تأثیر می‌گذارند (گویی قابل مشاهده هستند). هنگامی که مقدار false باشد، قوانین فاصله‌گذاری مبتنی بر کلاس نادیده گرفته می‌شود. متناظر با ویژگی OMML m:transp.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

ویژگی‌های کاراکتر کنترلی

**بازگشت:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

دریافت عناصر فرزند

**بازگشت:**
com.aspose.slides.IMathElement[]