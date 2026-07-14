---
title: IImage
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نماد یک تصویر رستر یا برداری است.
type: docs
url: /fa/com.aspose.slides/iimage/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

نماد یک تصویر رستر یا برداری است.

--------------------

این واسط یک انتزاع مشترک برای پردازش هر دو نوع تصویر رستر و برداری فراهم می‌کند. پیاده‌سازی‌ها ممکن است بسته به نوع تصویر پایه متفاوت باشند.
## متدها

| متد | توضیح |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | تصویر را در فایلی ذخیره می‌کند. |
| [save(String filename, int format)](#save-java.lang.String-int-) | تصویر را در فایلی با قالب مشخص ذخیره می‌کند. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | تصویر را در جریان (stream) با قالب مشخص ذخیره می‌کند. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | تصویر را در فایلی با قالب و کیفیت مشخص ذخیره می‌کند. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | تصویر را در جریان (stream) با قالب و کیفیت مشخص ذخیره می‌کند. |
| [getSize()](#getSize--) | اندازهٔ تصویر را دریافت می‌کند. |
| [getWidth()](#getWidth--) | عرض تصویر بر حسب پیکسل را دریافت می‌کند. |
| [getHeight()](#getHeight--) | ارتفاع تصویر بر حسب پیکسل را دریافت می‌کند. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

تصویر را در فایلی ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | java.lang.String | مسیر فایلی که تصویر در آن ذخیره می‌شود. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

تصویر را در فایلی با قالب مشخص ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | java.lang.String | مسیر فایلی که تصویر در آن ذخیره می‌شود. |
| format | int | قالب تصویر. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

تصویر را در جریان (stream) با قالب مشخص ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریانی که تصویر در آن ذخیره می‌شود. |
| format | int | قالب تصویر. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

تصویر را در فایلی با قالب و کیفیت مشخص ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | java.lang.String | مسیر فایلی که تصویر در آن ذخیره می‌شود. |
| format | int | قالب تصویر. |
| quality | int | کیفیت تصویر ذخیره‌شده (۰ تا ۱۰۰). این پارامتر فقط بر ذخیره‌سازی در [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) تأثیر دارد؛ برای تمام فرمت‌های دیگر نادیده گرفته می‌شود. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

تصویر را در جریان (stream) با قالب و کیفیت مشخص ذخیره می‌کند.

**پارامترها:**
| پارامتر | النوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریانی که تصویر در آن ذخیره می‌شود. |
| format | int | قالب تصویر. |
| quality | int | کیفیت تصویر ذخیره‌شده (۰ تا ۱۰۰). این پارامتر فقط بر ذخیره‌سازی در [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) تأثیر دارد؛ برای تمام فرمت‌های دیگر نادیده گرفته می‌شود. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

اندازهٔ تصویر را دریافت می‌کند.

**بازگشت:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

عرض تصویر بر حسب پیکسل را دریافت می‌کند.

**بازگشت:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

ارتفاع تصویر بر حسب پیکسل را دریافت می‌کند.

**بازگشت:**
int