---
title: HtmlGenerator
second_title: Aspose.Slides برای مرجع API جاوا
description: تولیدکننده Html.
type: docs
url: /fa/com.aspose.slides/htmlgenerator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

تولیدکننده Html.
## متدها

| متد | توضیح |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | متن قالب‌بندی‌شده HTML را اضافه می‌کند. |
| [addHtml(char[] html)](#addHtml-char---) | متن قالب‌بندی‌شده HTML را اضافه می‌کند. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | متن قالب‌بندی‌شده HTML را اضافه می‌کند. |
| [addText(String text)](#addText-java.lang.String-) | متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را با موجودیت‌های html جایگزین می‌سازد. |
| [addText(char[] text)](#addText-char---) | متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را با موجودیت‌های html جایگزین می‌سازد. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را با موجودیت‌های html جایگزین می‌سازد. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | مقدار صفت را نقل قول می‌کند و به فایل html اضافه می‌کند. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | مقدار صفت را نقل قول می‌کند و به فایل html اضافه می‌کند. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | مقدار صفت را نقل قول می‌کند و به فایل html اضافه می‌کند. |
| [getSlideImageSize()](#getSlideImageSize--) | اندازه تصویر اسلاید را برمی‌گرداند. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | واحدی را که اندازه تصویر اسلاید بر اساس آن مشخص می‌شود، برمی‌گرداند. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | کد CSS واحدی که اندازه تصویر اسلاید بر اساس آن مشخص می‌شود را برمی‌گرداند. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | اندیس اسلاید قبلاً رندر شده را برمی‌گرداند یا -1 اگر اسلاید اول در حال رندر باشد. |
| [getSlideIndex()](#getSlideIndex--) | اندیس اسلاید در حال رندر را برمی‌گرداند. |
| [getNextSlideIndex()](#getNextSlideIndex--) | اندیس اسلایدی که بعد از اسلاید جاری رندر خواهد شد را برمی‌گرداند یا -1 اگر اسلاید جاری آخرین اسلاید در حال رندر باشد. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```


متن قالب‌بندی‌شده HTML را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| html | java.lang.String | متنی که باید اضافه شود. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```


متن قالب‌بندی‌شده HTML را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| html | char[] | متنی که باید اضافه شود. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```


متن قالب‌بندی‌شده HTML را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| html | char[] | متنی که باید اضافه شود. |
| startIndex | int | اندیس شروع بخشی که باید اضافه شود. |
| length | int | طول بخشی که باید اضافه شود. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```


متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را با موجودیت‌های html جایگزین می‌سازد. شکست‌های خط و فضاهای خالی جایگزین نمی‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید اضافه شود. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```


متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را با موجودیت‌های html جایگزین می‌سازد. شکست‌های خط و فضاهای خالی جایگزین نمی‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | char[] | متنی که باید اضافه شود. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```


متن ساده را به فایل‌های html اضافه می‌کند و کاراکترهای ویژه را با موجودیت‌های html جایگزین می‌سازد. شکست‌های خط و فضاهای خالی جایگزین نمی‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | char[] | متنی که باید اضافه شود. |
| startIndex | int | اندیس شروع بخشی که باید اضافه شود. |
| length | int | طول بخشی که باید اضافه شود. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```


مقدار صفت را نقل قول می‌کند و به فایل html اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String | رشته مقدار صفت. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```


مقدار صفت را نقل قول می‌کند و به فایل html اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char[] | رشته مقدار صفت. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```


مقدار صفت را نقل قول می‌کند و به فایل html اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char[] | رشته مقدار صفت. |
| startIndex | int | اندیس شروع بخشی که باید اضافه شود. |
| length | int | طول بخشی که باید اضافه شود. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```


اندازه تصویر اسلاید را برمی‌گرداند. فقط خواندنی java.awt.geom.Dimension2D.

**باز می‌گرداند:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```


واحدی را که اندازه تصویر اسلاید بر اساس آن مشخص می‌شود، برمی‌گرداند. فقط خواندنی [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**باز می‌گرداند:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```


کد CSS واحدی که اندازه تصویر اسلاید بر اساس آن مشخص می‌شود را برمی‌گرداند. فقط خواندنی String.

**باز می‌گرداند:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```


اندیس اسلاید قبلاً رندر شده را برمی‌گرداند یا -1 اگر اسلاید اول در حال رندر باشد. فقط خواندنی int.

**باز می‌گرداند:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


اندیس اسلاید در حال رندر را برمی‌گرداند. فقط خواندنی int.

**باز می‌گرداند:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```


اندیس اسلایدی که بعد از اسلاید جاری رندر خواهد شد را برمی‌گرداند یا -1 اگر اسلاید جاری آخرین اسلاید در حال رندر باشد. فقط خواندنی int.

**باز می‌گرداند:**
int