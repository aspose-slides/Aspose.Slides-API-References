---
title: IImage
second_title: Aspose.Slides برای Java مرجع API
description: نشان‌دهنده یک تصویر رستر یا برداری است.
type: docs
url: /fa/com.aspose.slides/iimage/
---
**تمام رابط‌های پیاده‌سازی شده:**  
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

نشان‌دهنده یک تصویر رستر یا برداری است.

--------------------

این رابط یک انتزاع عمومی برای پردازش هم تصاویر رستر و هم تصاویر برداری ارائه می‌دهد. پیاده‌سازی‌ها ممکن است بسته به نوع تصویر زیرین متفاوت باشند.
## متدها

| متد | توضیح |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | تصویر را در یک فایل ذخیره می‌کند. |
| [save(String filename, int format)](#save-java.lang.String-int-) | تصویر را در یک فایل با فرمت مشخص ذخیره می‌کند. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | تصویر را در یک جریان با فرمت مشخص ذخیره می‌کند. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | تصویر را در یک فایل با فرمت و کیفیت مشخص ذخیره می‌کند. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | تصویر را در یک جریان با فرمت و کیفیت مشخص ذخیره می‌کند. |
| [getSize()](#getSize--) | اندازهٔ تصویر را دریافت می‌کند. |
| [getWidth()](#getWidth--) | عرض تصویر را بر حسب پیکسل دریافت می‌کند. |
| [getHeight()](#getHeight--) | ارتفاع تصویر را بر حسب پیکسل دریافت می‌کند. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

تصویر را در یک فایل ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | java.lang.String | مسیر فایلی که تصویر در آن ذخیره خواهد شد. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

تصویر را در یک فایل با فرمت مشخص ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | java.lang.String | مسیر فایلی که تصویر در آن ذخیره خواهد شد. |
| format | int | فرمت تصویر. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

تصویر را در یک جریان با فرمت مشخص ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریانی که تصویر در آن ذخیره خواهد شد. |
| format | int | فرمت تصویر. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

تصویر را در یک فایل با فرمت و کیفیت مشخص ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | java.lang.String | مسیر فایلی که تصویر در آن ذخیره خواهد شد. |
| format | int | فرمت تصویر. |
| quality | int | کیفیت تصویر ذخیره‌شده (۰ تا ۱۰۰). این پارامتر فقط برای ذخیره در [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) موثر است؛ برای سایر فرمت‌ها نادیده گرفته می‌شود. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

تصویر را در یک جریان با فرمت و کیفیت مشخص ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریانی که تصویر در آن ذخیره خواهد شد. |
| format | int | فرمت تصویر. |
| quality | int | کیفیت تصویر ذخیره‌شده (۰ تا ۱۰۰). این پارامتر فقط برای ذخیره در [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) موثر است؛ برای سایر فرمت‌ها نادیده گرفته می‌شود. |

### getSize() {#getSize--}
```
public abstract Dimension getSize()
```

اندازهٔ تصویر را دریافت می‌کند.

**بازمی‌گردد:**  
java.awt.Dimension
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

عرض تصویر را بر حسب پیکسل دریافت می‌کند.

**بازمی‌گردد:**  
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

ارتفاع تصویر را بر حسب پیکسل دریافت می‌کند.

**بازمی‌گردد:**  
int