---
title: CaptionsCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک مجموعه از زیرنویس‌های بسته است.
type: docs
url: /fa/com.aspose.slides/captionscollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

نمایانگر یک مجموعه از زیرنویس‌های بسته.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | زیرنویس‌های بسته را در ایندکس مشخص‌شده برمی‌گرداند. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | زیرنویس‌های بسته WebVTT را به انتهای مجموعه اضافه می‌کند. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | زیرنویس‌های بسته WebVTT را از یک جریان به انتهای مجموعه اضافه می‌کند. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | زیرنویس‌های بسته مشخص‌شده را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | زیرنویس‌های بسته را در ایندکس مشخص‌شده حذف می‌کند. |
| [clear()](#clear--) | تمام زیرنویس‌های بسته را از مجموعه حذف می‌کند. |
| [getCount()](#getCount--) | تعداد عناصر موجود در مجموعه را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند. |

### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

زیرنویس‌های بسته را در ایندکس مشخص‌شده برمی‌گرداند. فقط خواندنی [ICaptions](../../com.aspose.slides/icaptions).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ICaptions](../../com.aspose.slides/icaptions)

### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

زیرنویس‌های بسته WebVTT را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| label | java.lang.String | برچسب زیرنویس‌های بسته. |
| filePath | java.lang.String | مسیر به فایل WebVTT. |

**بازگشت:**
[ICaptions](../../com.aspose.slides/icaptions) - نمونهٔ [ICaptions](../../com.aspose.slides/icaptions) اضافه‌شده.

### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

زیرنویس‌های بسته WebVTT را از یک جریان به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| label | java.lang.String | برچسب زیرنویس‌های بسته. |
| stream | java.io.InputStream | جریان ورودی حاوی داده‌ها در فرمت WebVTT. |

**بازگشت:**
[ICaptions](../../com.aspose.slides/icaptions) - نمونهٔ [ICaptions](../../com.aspose.slides/icaptions) اضافه‌شده.

### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

زیرنویس‌های بسته مشخص‌شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | زیرنویس‌های بسته برای حذف. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

زیرنویس‌های بسته را در ایندکس مشخص‌شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس زیرنویس‌های بسته برای حذف. |

### clear() {#clear--}
```
public final void clear()
```

تمام زیرنویس‌های بسته را از مجموعه حذف می‌کند.

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد عناصر موجود در مجموعه را برمی‌گرداند. فقط خواندنی  int .

**بازگشت:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

یک شمارنده که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - یک  System.Collections.Generic.IEnumerator1  که می‌تواند برای پیمایش مجموعه استفاده شود.