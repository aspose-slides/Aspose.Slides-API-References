---
title: IPortionFormat
second_title: Aspose.Slides برای مرجع API جاوا
description: این کلاس حاوی ویژگی‌های قالب‌بندی بخش متن است.
type: docs
url: /fa/com.aspose.slides/iportionformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

این کلاس حاوی ویژگی‌های قالب‌بندی بخش متن است. بر خلاف [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

--------------------

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی بخش متن تعریف‌شده برای بخش خاص استفاده می‌شود. این به این معنی است که هنگام دریافت مقادیر، ارث‌بری اعمال نمی‌شود، بنابراین در بیشتر موارد مقادیر "نامشخص" دریافت می‌کنید.

برای دریافت مقادیر پارامترهای قالب‌بندی مؤثر شامل ارث‌بری، باید از متد [getEffective](../../com.aspose.slides/iportionformat\#getEffective) استفاده کنید که یک نمونهٔ [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) برمی‌گرداند.
## متدها

| متد | توضیح |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | شناسهٔ نشانک را بر می‌گرداند یا تنظیم می‌کند. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | شناسهٔ نشانک را بر می‌گرداند یا تنظیم می‌کند. |
| [getSmartTagClean()](#getSmartTagClean--) | تعیین می‌کند که آیا برچسب هوشمند باید تمیز شود یا نه. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | تعیین می‌کند که آیا برچسب هوشمند باید تمیز شود یا نه. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی بخش مؤثر را با اعمال ارث‌بری دریافت می‌کند. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


شناسهٔ نشانک را بر می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String.

**بازگشت:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```


شناسهٔ نشانک را بر می‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


تعیین می‌کند که آیا برچسب هوشمند باید تمیز شود یا نه. بدون اعمال ارث‌بری. خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```


تعیین می‌کند که آیا برچسب هوشمند باید تمیز شود یا نه. بدون اعمال ارث‌بری. خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```


داده‌های قالب‌بندی بخش مؤثر را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - یک [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).