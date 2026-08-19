---
title: Output
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر مجموعه‌ای از عناصر خروجی برای IWebDocument است.
type: docs
url: /fa/com.aspose.slides/output/
---
**Inheritance:**
java.lang.Object
```
public final class Output
```

نمایانگر مجموعه‌ای از عناصر خروجی برای IWebDocument است.
## متدها

| متد | توضیح |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | یک عنصر خروجی برای شیء زمینه اضافه می‌کند. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | یک عنصر خروجی برای تصویر اضافه می‌کند. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | یک عنصر خروجی برای تصویر اضافه می‌کند. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | یک عنصر خروجی برای ویدئو اضافه می‌کند. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | یک عنصر خروجی برای صوت اضافه می‌کند. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | یک عنصر فایل خروجی برای قلم مشخص‌شده ایجاد و اضافه می‌کند. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | یک عنصر خروجی برای محتوای متنی اضافه می‌کند. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | منبع را به فایل خروجی متصل می‌کند. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | مسیر منبع داده‌شده را برمی‌گرداند. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```


یک عنصر خروجی برای شیء زمینه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| templateKey | java.lang.String | کلید الگوی استفاده‌شده برای تبدیل شیء زمینه قبل از خروجی. |
| contextObject | TContextObject | شیء زمینه. |

**بازگشت:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شی برای شیء زمینه.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```


یک عنصر خروجی برای تصویر اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویر برای خروجی. |

**بازگشت:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شی برای تصویر.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```


یک عنصر خروجی برای تصویر اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| image | [IImage](../../com.aspose.slides/iimage) | تصویر برای خروجی. |

**بازگشت:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شی برای تصویر.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```


یک عنصر خروجی برای ویدئو اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| video | [IVideo](../../com.aspose.slides/ivideo) | ویدئو برای خروجی. |

**بازگشت:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شی برای ویدئو.
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```


یک عنصر خروجی برای صوت اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | صوت برای خروجی. |

**بازگشت:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شی برای صوت.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```


یک عنصر فایل خروجی برای قلم مشخص‌شده ایجاد و اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیری که خروجی قلم در آن ذخیره خواهد شد. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | داده‌های قلم که باید در خروجی نوشته شود. |
| fontStyle | int | سبک قلم (مانند Regular، Bold، Italic). |

**بازگشت:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - یک نمونه [IOutputFile](../../com.aspose.slides/ioutputfile) برای قلم تولید‌شده.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```


یک عنصر خروجی برای محتوای متنی اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| textContent | java.lang.String | محتوا برای خروجی. |

**بازگشت:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شی برای محتوای متنی.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```


منبع را به فایل خروجی متصل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | فایل خروجی. |
| obj | java.lang.Object | شیء منبع. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```


مسیر منبع داده‌شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | شیء منبع. |

**بازگشت:**
java.lang.String - مسیر منبع.