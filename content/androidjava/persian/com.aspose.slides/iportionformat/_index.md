---
title: IPortionFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است.
type: docs
url: /fa/com.aspose.slides/iportionformat/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

--------------------

این کلاس برای برگرداندن و دستکاری ویژگی‌های قالب‌بندی بخش متن که برای قسمت خاص تعریف شده‌اند، استفاده می‌شود. این بدین معنی است که هنگام دریافت مقادیر، وراثت اعمال نمی‌شود، به‌طوری‌که در بیشتر موارد مقادیر "undefined" دریافت می‌کنید.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی شامل وراثت، باید از متد [getEffective](../../com.aspose.slides/iportionformat\#getEffective) استفاده کنید که یک نمونه [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) را برمی‌گرداند.
## متدها

| متد | توضیح |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | بازگرداندن یا تنظیم شناسه نشانک. قابل خواندن/نوشتن String. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | بازگرداندن یا تنظیم شناسه نشانک. قابل خواندن/نوشتن String. |
| [getSmartTagClean()](#getSmartTagClean--) | تعیین می‌کند که آیا برچسب هوشمند باید پاک شود. وراثت اعمال نمی‌شود. قابل خواندن/نوشتن boolean. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | تعیین می‌کند که آیا برچسب هوشمند باید پاک شود. وراثت اعمال نمی‌شود. قابل خواندن/نوشتن boolean. |
| [getEffective()](#getEffective--) | دریافت داده‌های قالب‌بندی بخش مؤثر با اعمال وراثت. |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

بازگرداندن یا تنظیم شناسه نشانک. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

بازگرداندن یا تنظیم شناسه نشانک. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

تعیین می‌کند که آیا برچسب هوشمند باید پاک شود. وراثت اعمال نمی‌شود. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

تعیین می‌کند که آیا برچسب هوشمند باید پاک شود. وراثت اعمال نمی‌شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی بخش مؤثر را با اعمال وراثت دریافت می‌کند.

**بازگشت:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).