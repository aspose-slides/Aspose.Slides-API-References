---
title: ICaptionsCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش یک مجموعه از زیرنویس‌های بسته.
type: docs
url: /fa/com.aspose.slides/icaptionscollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

نمایش یک مجموعه از زیرنویس‌های بسته.
## متدها

| متد | شرح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | زیرنویس‌های بسته را در شاخص مشخص شده برمی‌گرداند. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | زیرنویس‌های بسته WebVTT را به انتهای مجموعه اضافه می‌کند. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | زیرنویس‌های بسته WebVTT را از یک جریان به انتهای مجموعه اضافه می‌کند. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | زیرنویس‌های بسته مشخص شده را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | زیرنویس‌های بسته را در شاخص مشخص شده حذف می‌کند. |
| [clear()](#clear--) | تمام زیرنویس‌های بسته را از مجموعه حذف می‌کند. |
| [getCount()](#getCount--) | تعداد عناصر موجود در مجموعه را برمی‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```


زیرنویس‌های بسته را در شاخص مشخص شده برمی‌گرداند. فقط-خواندنی [ICaptions](../../com.aspose.slides/icaptions).

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


زیرنویس‌های بسته WebVTT را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| label | java.lang.String | برچسب زیرنویس‌های بسته. |
| filePath | java.lang.String | مسیر فایل WebVTT. |

**بازگشت:**
[ICaptions](../../com.aspose.slides/icaptions) - نمونه [ICaptions](../../com.aspose.slides/icaptions) اضافه‌شده.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


زیرنویس‌های بسته WebVTT را از یک جریان به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| label | java.lang.String | برچسب زیرنویس‌های بسته. |
| stream | java.io.InputStream | جریان ورودی حاوی داده‌ها به فرمت WebVTT. |

**بازگشت:**
[ICaptions](../../com.aspose.slides/icaptions) - نمونه [ICaptions](../../com.aspose.slides/icaptions) اضافه‌شده.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


زیرنویس‌های بسته مشخص شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | زیرنویس‌های بسته برای حذف. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


زیرنویس‌های بسته را در شاخص مشخص شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص زیرنویس‌های بسته برای حذف. |

### clear() {#clear--}
```
public abstract void clear()
```


تمام زیرنویس‌های بسته را از مجموعه حذف می‌کند.

### getCount() {#getCount--}
```
public abstract int getCount()
```


تعداد عناصر موجود در مجموعه را برمی‌گرداند. فقط-خواندنی int .

**بازگشت:**
int