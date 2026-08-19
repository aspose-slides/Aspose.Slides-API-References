---
title: IMathPhantom
second_title: مرجع API Aspose.Slides برای Java
description: یک شیء ریاضی فانتوم به نام ltmphantgt را نشان می‌دهد که بدون لزوماً نمایش، بر چیدمان عنصر فرزند خود اثر می‌گذارد.
type: docs
url: /fa/com.aspose.slides/imathphantom/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

یک شیء ریاضی فانتوم (<m:phant>) را توصیف می‌کند که بدون لزوماً نمایش آن، بر چیدمان عنصر فرزندش اثر می‌گذارد. فانتوم می‌تواند عبارت پایه را مخفی کند در حالی که عرض، ارتفاع یا عمق آن را حفظ می‌کند تا فرمول‌ها را هم‌راستا یا فضا را رزرو کند. رفتار نمایانی و هندسی توسط ویژگی‌هایی مانند Show، ZeroWid، ZeroAsc، ZeroDesc و Transp کنترل می‌شود.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // مخفی کردن محتوا
>  phantom.setZeroWidth(false);     // حفظ عرض
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getShow()](#getShow--) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود یا نه. |
| [setShow(boolean value)](#setShow-boolean-) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود یا نه. |
| [getZeroWidth()](#getZeroWidth--) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عرض عنصر پایه به‌عنوان صفر در نظر گرفته شود یا نه. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عرض عنصر پایه به‌عنوان صفر در نظر گرفته شود یا نه. |
| [getZeroAsc()](#getZeroAsc--) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا صعود (ارتفاع بالای خط پایه) عنصر پایه به‌عنوان صفر در نظر گرفته شود یا نه. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا صعود (ارتفاع بالای خط پایه) عنصر پایه به‌عنوان صفر در نظر گرفته شود یا نه. |
| [getZeroDesc()](#getZeroDesc--) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا نزول (عمق زیر خط پایه) عنصر پایه به‌عنوان صفر در نظر گرفته شود یا نه. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا نزول (عمق زیر خط پایه) عنصر پایه به‌عنوان صفر در نظر گرفته شود یا نه. |
| [getTransp()](#getTransp--) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف باشد یا نه. |
| [setTransp(boolean value)](#setTransp-boolean-) | یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف باشد یا نه. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
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
public abstract boolean getShow()
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود یا نه.

--------------------

When false, the base element is hidden but may still occupy space depending on other phantom settings. Corresponds to the OMML attribute m:show.

**بازگشت:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عنصر پایه نمایش داده می‌شود یا نه.

--------------------

When false, the base element is hidden but may still occupy space depending on other phantom settings. Corresponds to the OMML attribute m:show.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عرض عنصر پایه به‌عنوان صفر در نظر گرفته شود یا نه.

--------------------

When true, the phantom does not reserve horizontal space for its base. Corresponds to the OMML attribute m:zeroWid.

**بازگشت:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا عرض عنصر پایه به‌عنوان صفر در نظر گرفته شود یا نه.

--------------------

When true, the phantom does not reserve horizontal space for its base. Corresponds to the OMML attribute m:zeroWid.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا صعود (ارتفاع بالای خط پایه) عنصر پایه به‌عنوان صفر در نظر گرفته شود یا نه.

--------------------

When true, the phantom does not raise the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroAsc.

**بازگشت:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا صعود (ارتفاع بالای خط پایه) عنصر پایه به‌عنوان صفر در نظر گرفته شود یا نه.

--------------------

When true, the phantom does not raise the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroAsc.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا نزول (عمق زیر خط پایه) عنصر پایه به‌عنوان صفر در نظر گرفته شود یا نه.

--------------------

When true, the phantom does not lower the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroDesc.

**بازگشت:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا نزول (عمق زیر خط پایه) عنصر پایه به‌عنوان صفر در نظر گرفته شود یا نه.

--------------------

When true, the phantom does not lower the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroDesc.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف باشد یا نه.

--------------------

When true, operators and symbols inside the phantom still affect mathematical spacing around the phantom (as if visible). When false, class-based spacing is ignored. Corresponds to the OMML attribute m:transp.

**بازگشت:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

یک مقدار را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا فانتوم برای قوانین فاصله‌گذاری مبتنی بر کلاس شفاف باشد یا نه.

--------------------

When true, operators and symbols inside the phantom still affect mathematical spacing around the phantom (as if visible). When false, class-based spacing is ignored. Corresponds to the OMML attribute m:transp.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |