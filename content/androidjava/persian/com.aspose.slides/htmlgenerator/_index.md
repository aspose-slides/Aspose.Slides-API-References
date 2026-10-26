---
title: HtmlGenerator
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: مولد HTML.
type: docs
url: /fa/com.aspose.slides/htmlgenerator/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

مولد HTML.
## متدها

| متد | توضیح |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | متن HTML قالب‌بندی‌شده را اضافه می‌کند. |
| [addHtml(char[] html)](#addHtml-char---) | متن HTML قالب‌بندی‌شده را اضافه می‌کند. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | متن HTML قالب‌بندی‌شده را اضافه می‌کند. |
| [addText(String text)](#addText-java.lang.String-) | متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای خاص را با موجودیت‌های html جایگزین می‌کند. |
| [addText(char[] text)](#addText-char---) | متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای خاص را با موجودیت‌های html جایگزین می‌کند. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای خاص را با موجودیت‌های html جایگزین می‌کند. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | مقدار صفت را در نقل‌قول می‌گیرد و به فایل html اضافه می‌کند. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | مقدار صفت را در نقل‌قول می‌گیرد و به فایل html اضافه می‌کند. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | مقدار صفت را در نقل‌قول می‌گیرد و به فایل html اضافه می‌کند. |
| [getSlideImageSize()](#getSlideImageSize--) | اندازه تصویر اسلاید را برمی‌گرداند. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | یک واحد که اندازه تصویر اسلاید بر اساس آن مشخص می‌شود را برمی‌گرداند. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | کد CSS واحدی که اندازه تصویر اسلاید بر اساس آن مشخص می‌شود را برمی‌گرداند. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | شاخص اسلاید پیشین رندرسازی شده را برمی‌گرداند یا -1 اگر اسلاید اول در حال رندرسازی باشد. |
| [getSlideIndex()](#getSlideIndex--) | شاخص اسلاید در حال رندرسازی را برمی‌گرداند. |
| [getNextSlideIndex()](#getNextSlideIndex--) | شاخص اسلایدی که پس از اسلاید فعلی رندرسازی خواهد شد را برمی‌گرداند یا -1 اگر در حال رندرسازی آخرین اسلاید باشد. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

متن HTML قالب‌بندی‌شده را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| html | java.lang.String | متنی که باید اضافه شود. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

متن HTML قالب‌بندی‌شده را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| html | char[] | متنی که باید اضافه شود. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

متن HTML قالب‌بندی‌شده را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| html | char[] | متنی که باید اضافه شود. |
| startIndex | int | اندیس شروع قسمتی که باید اضافه شود. |
| length | int | طول قسمتی که باید اضافه شود. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای خاص را با موجودیت‌های html جایگزین می‌کند. خط‌های جدید و فاصله‌ها جایگزین نمی‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید اضافه شود. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای خاص را با موجودیت‌های html جایگزین می‌کند. خط‌های جدید و فاصله‌ها جایگزین نمی‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | char[] | متنی که باید اضافه شود. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای خاص را با موجودیت‌های html جایگزین می‌کند. خط‌های جدید و فاصله‌ها جایگزین نمی‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | char[] | متنی که باید اضافه شود. |
| startIndex | int | اندیس شروع قسمتی که باید اضافه شود. |
| length | int | طول قسمتی که باید اضافه شود. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

مقدار صفت را در نقل‌قول می‌گیرد و به فایل html اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String | رشته مقدار صفت. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

مقدار صفت را در نقل‌قول می‌گیرد و به فایل html اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char[] | رشته مقدار صفت. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

مقدار صفت را در نقل‌قول می‌گیرد و به فایل html اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char[] | رشته مقدار صفت. |
| startIndex | int | اندیس شروع قسمتی که باید اضافه شود. |
| length | int | طول قسمتی که باید اضافه شود. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```

اندازه تصویر اسلاید را برمی‌گرداند. فقط-خواندنی [SizeF](../../com.aspose.slides.android/sizef).

**بازگشت:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

یک واحد که اندازه تصویر اسلاید بر اساس آن مشخص می‌شود را برمی‌گرداند. فقط-خواندنی [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**بازگشت:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

کد CSS واحدی که اندازه تصویر اسلاید بر اساس آن مشخص می‌شود را برمی‌گرداند. فقط-خواندنی String.

**بازگشت:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

شاخص اسلاید پیشین رندرسازی شده را برمی‌گرداند یا -1 اگر اسلاید اول در حال رندرسازی باشد. فقط-خواندنی int.

**بازگشت:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

شاخص اسلاید در حال رندرسازی را برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

شاخص اسلایدی که پس از اسلاید فعلی رندرسازی خواهد شد را برمی‌گرداند یا -1 اگر در حال رندرسازی آخرین اسلاید باشد. فقط-خواندنی int.

**بازگشت:**
int