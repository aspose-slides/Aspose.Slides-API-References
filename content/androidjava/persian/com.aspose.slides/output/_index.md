---
title: Output
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از عناصر خروجی برای IWebDocument است.
type: docs
url: /fa/com.aspose.slides/output/
---
**وارثی:**
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
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | یک عنصر خروجی برای ویدیو اضافه می‌کند. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | یک عنصر فایل خروجی برای قلم مشخص شده ایجاد و اضافه می‌کند. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | یک عنصر خروجی برای محتوای متنی اضافه می‌کند. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | منبع را به فایل خروجی بایند می‌کند. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | مسیر یک منبع داده شده را برمی‌گرداند. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

یک عنصر خروجی برای شیء زمینه اضافه می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| templateKey | java.lang.String | کلید قالب مورد استفاده برای تبدیل شیء زمینه قبل از خروجی. |
| contextObject | TContextObject | شیء زمینه. |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شیء برای شیء زمینه.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

یک عنصر خروجی برای تصویر اضافه می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویر برای خروجی. |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شیء برای تصویر.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

یک عنصر خروجی برای تصویر اضافه می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| image | [IImage](../../com.aspose.slides/iimage) | تصویر برای خروجی. |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شیء برای تصویر.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

یک عنصر خروجی برای ویدیو اضافه می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| video | [IVideo](../../com.aspose.slides/ivideo) | ویدیو برای خروجی. |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شیء برای ویدیو.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

یک عنصر فایل خروجی برای قلم مشخص شده ایجاد و اضافه می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر فایلی که خروجی قلم در آن ذخیره خواهد شد. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | داده‌های قلم برای نوشتن در خروجی. |
| fontStyle | int | سبک قلم (مثلاً Regular, Bold, Italic). |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - یک نمونه از [IOutputFile](../../com.aspose.slides/ioutputfile) برای قلم تولید شده.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

یک عنصر خروجی برای محتوای متنی اضافه می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| textContent | java.lang.String | محتوا برای خروجی. |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شیء برای محتوای متنی.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

منبع را به فایل خروجی بایند می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | فایل خروجی. |
| obj | java.lang.Object | شیء منبع. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

مسیر یک منبع داده شده را برمی‌گرداند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | شیء منبع. |

**Returns:**
java.lang.String - مسیر منبع.