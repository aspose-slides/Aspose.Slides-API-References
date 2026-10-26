---
title: Output
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهندهٔ مجموعه‌ای از عناصر خروجی برای IWebDocument.
type: docs
url: /fa/com.aspose.slides/output/
---
**ارث‌بری:**  
java.lang.Object  
```
public final class Output
```

نمایش‌دهندهٔ مجموعه‌ای از عناصر خروجی برای IWebDocument.

## متدها

| متد | توضیح |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | یک عنصر خروجی برای شیء context object اضافه می‌کند. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | یک عنصر خروجی برای تصویر اضافه می‌کند. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | یک عنصر خروجی برای تصویر اضافه می‌کند. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | یک عنصر خروجی برای ویدیو اضافه می‌کند. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | یک عنصر خروجی برای صوت اضافه می‌کند. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | یک عنصر فایل خروجی برای فونت مشخص‌شده را ایجاد و اضافه می‌کند. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | یک عنصر خروجی برای محتوا متنی اضافه می‌کند. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | منبع را به فایل خروجی متصل می‌کند. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | مسیر را برای یک منبع داده شده برمی‌گرداند. |

### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

یک عنصر خروجی برای شیء context object اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| templateKey | java.lang.String | کلید قالب مورد استفاده برای تبدیل شیء context object قبل از خروجی. |
| contextObject | TContextObject | شیء context object. |

**بازگشت:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شیء برای context object.

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
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شیء برای تصویر.

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
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شیء برای تصویر.

### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

یک عنصر خروجی برای ویدیو اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| video | [IVideo](../../com.aspose.slides/ivideo) | ویدیو برای خروجی. |

**بازگشت:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شیء برای ویدیو.

### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

یک عنصر خروجی برای صوت اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | صدا برای خروجی. |

**بازگشت:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شیء برای صوت.

### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

یک عنصر فایل خروجی برای فونت مشخص‌شده را ایجاد و اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر فایلی که خروجی فونت در آن ذخیره خواهد شد. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | دادهٔ فونتی که باید به خروجی نوشته شود. |
| fontStyle | int | سبک فونت (مثلاً Regular، Bold، Italic). |

**بازگشت:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - یک نمونهٔ [IOutputFile](../../com.aspose.slides/ioutputfile) برای فونت تولید شده.

### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

یک عنصر خروجی برای محتوا متنی اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیر خروجی. |
| textContent | java.lang.String | محتوای متنی برای خروجی. |

**بازگشت:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) شیء برای محتوا متنی.

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

مسیر را برای یک منبع داده شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | شیء منبع. |

**بازگشت:**
java.lang.String - مسیر منبع.