---
title: IHtmlGenerator
second_title: Aspose.Slides for Java API Reference
description: Html generator.
type: docs
url: /fa/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

تولیدکننده HTML.
## متدها

| متد | توضیح |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | متن HTML قالب‌بندی‌شده را اضافه می‌کند. |
| [addHtml(char[] html)](#addHtml-char---) | متن HTML قالب‌بندی‌شده را اضافه می‌کند. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | متن HTML قالب‌بندی‌شده را اضافه می‌کند. |
| [addText(String text)](#addText-java.lang.String-) | متن ساده را به فایل‌های HTML اضافه می‌کند و کاراکترهای خاص را با نهادهای HTML جایگزین می‌نماید. |
| [addText(char[] text)](#addText-char---) | متن ساده را به فایل‌های HTML اضافه می‌کند و کاراکترهای خاص را با نهادهای HTML جایگزین می‌نماید. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | متن ساده را به فایل‌های HTML اضافه می‌کند و کاراکترهای خاص را با نهادهای HTML جایگزین می‌نماید. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | مقدار ویژگی را به صورت نقل‌قول در می‌آورد و به فایل HTML اضافه می‌کند. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | مقدار ویژگی را به صورت نقل‌قول در می‌آورد و به فایل HTML اضافه می‌کند. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | مقدار ویژگی را به صورت نقل‌قول در می‌آورد و به فایل HTML اضافه می‌کند. |
| [getSlideImageSize()](#getSlideImageSize--) | اندازه تصویر اسلاید را برمی‌گرداند. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | واحدی که اندازه تصویر اسلاید در آن مشخص می‌شود را برمی‌گرداند. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | کد CSS واحدی که اندازه تصویر اسلاید در آن مشخص می‌شود را برمی‌گرداند. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | شاخص اسلاید قبلاً رندرشده را برمی‌گرداند یا -1 اگر اولین اسلاید در حال رندر باشد. |
| [getSlideIndex()](#getSlideIndex--) | شاخص اسلاید در حال رندر شدن را برمی‌گرداند. |
| [getNextSlideIndex()](#getNextSlideIndex--) | شاخص اسلایدی که پس از اسلاید جاری رندر خواهد شد را برمی‌گرداند یا -1 اگر در حال رندر آخرین اسلاید باشد. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

متن HTML قالب‌بندی‌شده را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| html | java.lang.String | متنی برای اضافه کردن. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

متن HTML قالب‌بندی‌شده را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| html | char[] | متنی برای اضافه کردن. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

متن HTML قالب‌بندی‌شده را اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| html | char[] | متنی برای اضافه کردن. |
| startIndex | int | شاخص شروع بخشی که باید اضافه شود. |
| length | int | طول بخشی که باید اضافه شود. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

متن ساده را به فایل‌های HTML اضافه می‌کند و کاراکترهای خاص را با نهادهای HTML جایگزین می‌نماید. شکست‌خط‌ها و فضاهای خالی جایگزین نمی‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی برای اضافه کردن. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

متن ساده را به فایل‌های HTML اضافه می‌کند و کاراکترهای خاص را با نهادهای HTML جایگزین می‌نماید. شکست‌خط‌ها و فضاهای خالی جایگزین نمی‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | char[] | متنی برای اضافه کردن. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

متن ساده را به فایل‌های HTML اضافه می‌کند و کاراکترهای خاص را با نهادهای HTML جایگزین می‌نماید. شکست‌خط‌ها و فضاهای خالی جایگزین نمی‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | char[] | متنی برای اضافه کردن. |
| startIndex | int | شاخص شروع بخشی که باید اضافه شود. |
| length | int | طول بخشی که باید اضافه شود. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

مقدار ویژگی را به صورت نقل‌قول در می‌آورد و به فایل HTML اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String | رشته مقدار ویژگی. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

مقدار ویژگی را به صورت نقل‌قول در می‌آورد و به فایل HTML اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char[] | رشته مقدار ویژگی. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

مقدار ویژگی را به صورت نقل‌قول در می‌آورد و به فایل HTML اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char[] | رشته مقدار ویژگی. |
| startIndex | int | شاخص شروع بخشی که باید اضافه شود. |
| length | int | طول بخشی که باید اضافه شود. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract Dimension2D getSlideImageSize()
```

اندازه تصویر اسلاید را برمی‌گرداند. فقط-خواندنی java.awt.geom.Dimension2D.

**بازگشت:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

واحدی که اندازه تصویر اسلاید در آن مشخص می‌شود را برمی‌گرداند. فقط-خواندنی [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**بازگشت:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

کد CSS واحدی که اندازه تصویر اسلاید در آن مشخص می‌شود را برمی‌گرداند. فقط-خواندنی String.

**بازگشت:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

شاخص اسلاید قبلاً رندرشده را برمی‌گرداند یا -1 اگر اولین اسلاید در حال رندر باشد. فقط-خواندنی int.

**بازگشت:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

شاخص اسلاید در حال رندر شدن را برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

شاخص اسلایدی که پس از اسلاید جاری رندر خواهد شد را برمی‌گرداند یا -1 اگر در حال رندر آخرین اسلاید باشد. فقط-خواندنی int.

**بازگشت:**
int