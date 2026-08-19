---
title: ICaptionsCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک مجموعه از زیرنویس‌های بسته شده است.
type: docs
url: /fa/com.aspose.slides/icaptionscollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

نمایانگر یک مجموعه از زیرنویس‌های بسته شده است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | زیرنویس‌های بسته شده را در ایندکس مشخص شده برمی‌گرداند. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | زیرنویس‌های بسته شده WebVTT را به انتهای مجموعه اضافه می‌کند. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | زیرنویس‌های بسته شده WebVTT را از یک جریان به انتهای مجموعه اضافه می‌کند. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | زیرنویس‌های بسته شده مشخص‌شده را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | زیرنویس‌های بسته شده را در ایندکس مشخص شده حذف می‌کند. |
| [clear()](#clear--) | تمام زیرنویس‌های بسته شده را از مجموعه حذف می‌کند. |
| [getCount()](#getCount--) | تعداد عناصر موجود در مجموعه را برمی‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```

زیرنویس‌های بسته شده را در ایندکس مشخص شده برمی‌گرداند. فقط‌خواندنی [ICaptions](../../com.aspose.slides/icaptions).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```

زیرنویس‌های بسته شده WebVTT را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| label | java.lang.String | برچسب زیرنویس‌های بسته شده. |
| filePath | java.lang.String | مسیر فایل WebVTT. |

**بازگشت:**
[ICaptions](../../com.aspose.slides/icaptions) - نمونهٔ [ICaptions](../../com.aspose.slides/icaptions) اضافه‌شده.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```

زیرنویس‌های بسته شده WebVTT را از یک جریان به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| label | java.lang.String | برچسب زیرنویس‌های بسته شده. |
| stream | java.io.InputStream | جریان ورودی حاوی داده‌های به فرمت WebVTT. |

**بازگشت:**
[ICaptions](../../com.aspose.slides/icaptions) - نمونهٔ [ICaptions](../../com.aspose.slides/icaptions) اضافه‌شده.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

زیرنویس‌های بسته شده مشخص‌شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | زیرنویس‌های بسته شده برای حذف. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

زیرنویس‌های بسته شده را در ایندکس مشخص شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس زیرنویس‌های بسته شده برای حذف. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام زیرنویس‌های بسته شده را از مجموعه حذف می‌کند.

### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد عناصر موجود در مجموعه را برمی‌گرداند. فقط‌خواندنی int .

**بازگشت:**
int