---
title: CaptionsCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر مجموعه‌ای از زیرنویس‌های بسته است.
type: docs
url: /fa/com.aspose.slides/captionscollection/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

نمایانگر یک مجموعه از زیرنویس‌های بسته است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | زیرنویس‌های بسته را در اندیس مشخص شده برمی‌گرداند. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | زیرنویس‌های بسته WebVTT را به انتهای مجموعه اضافه می‌کند. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | زیرنویس‌های بسته WebVTT را از یک جریان به انتهای مجموعه اضافه می‌کند. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | زیرنویس‌های بسته مشخص شده را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | زیرنویس‌های بسته را در اندیس مشخص شده حذف می‌کند. |
| [clear()](#clear--) | تمام زیرنویس‌های بسته را از مجموعه حذف می‌کند. |
| [getCount()](#getCount--) | تعداد عناصر موجود در مجموعه را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارشگر که از طریق مجموعه تکرار می‌کند را برمی‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

زیرنویس‌های بسته را در اندیس مشخص شده برمی‌گرداند. فقط خواندنی [ICaptions](../../com.aspose.slides/icaptions).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگرداندن:**
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
| filePath | java.lang.String | مسیر فایل WebVTT. |

**بازگرداندن:**
[ICaptions](../../com.aspose.slides/icaptions) - نمونه [ICaptions](../../com.aspose.slides/icaptions) اضافه شده.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

زیرنویس‌های بسته WebVTT را از یک جریان به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| label | java.lang.String | برچسب زیرنویس‌های بسته. |
| stream | java.io.InputStream | جریان ورودی حاوی داده‌ها به فرمت WebVTT. |

**بازگرداندن:**
[ICaptions](../../com.aspose.slides/icaptions) - نمونه [ICaptions](../../com.aspose.slides/icaptions) اضافه شده.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

زیرنویس‌های بسته مشخص شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | زیرنویس‌های بسته‌ای که باید حذف شوند. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

زیرنویس‌های بسته را در اندیس مشخص شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس زیرنویس‌های بسته‌ای که باید حذف شوند. |

### clear() {#clear--}
```
public final void clear()
```

تمام زیرنویس‌های بسته را از مجموعه حذف می‌کند.

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد عناصر موجود در مجموعه را برمی‌گرداند. فقط خواندنی int .

**بازگرداندن:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

یک شمارشگر که از طریق مجموعه تکرار می‌کند را برمی‌گرداند.

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - A  System.Collections.Generic.IEnumerator1  that can be used to iterate through the collection.