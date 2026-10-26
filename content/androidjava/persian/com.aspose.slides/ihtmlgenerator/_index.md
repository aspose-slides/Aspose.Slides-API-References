---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Html generator.
type: docs
url: /fa/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

ژنراتور Html.

## روش‌ها

| Method | Description |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | متن قالب‌بندی شده HTML را اضافه می‌کند. |
| [addHtml(char[] html)](#addHtml-char---) | متن قالب‌بندی شده HTML را اضافه می‌کند. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | متن قالب‌بندی شده HTML را اضافه می‌کند. |
| [addText(String text)](#addText-java.lang.String-) | متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را با موجودیت‌های html جایگزین می‌سازد. |
| [addText(char[] text)](#addText-char---) | متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را با موجودیت‌های html جایگزین می‌سازد. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را با موجودیت‌های html جایگزین می‌سازد. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | مقدار ویژگی را درون نقل‌قول می‌گیرد و به فایل html اضافه می‌کند. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | مقدار ویژگی را درون نقل‌قول می‌گیرد و به فایل html اضافه می‌کند. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | مقدار ویژگی را درون نقل‌قول می‌گیرد و به فایل html اضافه می‌کند. |
| [getSlideImageSize()](#getSlideImageSize--) | اندازه تصویر اسلاید را برمی‌گرداند. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | واحدی که اندازه تصویر اسلاید بر اساس آن مشخص شده است را برمی‌گرداند. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | کد css واحدی که اندازه تصویر اسلاید بر اساس آن مشخص شده است را برمی‌گرداند. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | نمایه اسلاید قبلاً رندر شده را برمی‌گرداند یا -1 اگر اولین اسلاید در حال رندر باشد. |
| [getSlideIndex()](#getSlideIndex--) | نمایه اسلاید در حال رندر را برمی‌گرداند. |
| [getNextSlideIndex()](#getNextSlideIndex--) | نمایه اسلایدی که پس از اسلاید جاری رندر خواهد شد را برمی‌گرداند یا -1 اگر در حال رندر آخرین اسلاید باشد. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

متن قالب‌بندی شده HTML را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| html | java.lang.String | متن برای افزودن. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

متن قالب‌بندی شده HTML را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| html | char[] | متن برای افزودن. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

متن قالب‌بندی شده HTML را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| html | char[] | متن برای افزودن. |
| startIndex | int | ایندکس شروع بخشی که باید اضافه شود. |
| length | int | طول بخشی که باید اضافه شود. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را با موجودیت‌های html جایگزین می‌سازد. خط‌توقف‌ها و فضاهای خالی جایگزین نمی‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن برای افزودن. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را با موجودیت‌های html جایگزین می‌سازد. خط‌توقف‌ها و فضاهای خالی جایگزین نمی‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | char[] | متن برای افزودن. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را با موجودیت‌های html جایگزین می‌سازد. خط‌توقف‌ها و فضاهای خالی جایگزین نمی‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | char[] | متن برای افزودن. |
| startIndex | int | ایندکس شروع بخشی که باید اضافه شود. |
| length | int | طول بخشی که باید اضافه شود. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

مقدار ویژگی را درون نقل‌قول می‌گیرد و به فایل html اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String | رشته مقدار ویژگی. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

مقدار ویژگی را درون نقل‌قول می‌گیرد و به فایل html اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char[] | رشته مقدار ویژگی. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

مقدار ویژگی را درون نقل‌قول می‌گیرد و به فایل html اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char[] | رشته مقدار ویژگی. |
| startIndex | int | ایندکس شروع بخشی که باید اضافه شود. |
| length | int | طول بخشی که باید اضافه شود. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

اندازه تصویر اسلاید را برمی‌گرداند. فقط-خواندنی [SizeF](../../com.aspose.slides.android/sizef).

**بازگشت:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

واحدی که اندازه تصویر اسلاید بر اساس آن مشخص شده است را برمی‌گرداند. فقط-خواندنی [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**بازگشت:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

کد css واحدی که اندازه تصویر اسلاید بر اساس آن مشخص شده است را برمی‌گرداند. فقط-خواندنی String.

**بازگشت:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

نمایه اسلاید قبلاً رندر شده را برمی‌گرداند یا -1 اگر اولین اسلاید در حال رندر باشد. فقط-خواندنی int.

**بازگشت:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

نمایه اسلاید در حال رندر را برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

نمایه اسلایدی که پس از اسلاید جاری رندر خواهد شد را برمی‌گرداند یا -1 اگر در حال رندر آخرین اسلاید باشد. فقط-خواندنی int.

**بازگشت:**
int