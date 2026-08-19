---
title: Merger
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر گروهی از متدها برای ادغام ارائه‌های PowerPoint با فرمت یکسان در یک فایل است.
type: docs
url: /fa/com.aspose.slides/merger/
---
**ارث‌بری:**  
java.lang.Object  
```
public class Merger
```

نمایانگر گروهی از متدها برای ادغام ارائه‌های PowerPoint با فرمت یکسان در یک فایل است.

## متدها

| متد | توضیح |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | چند ارائهٔ PowerPoint با فرمت یکسان را در یک فایل ارائه ادغام می‌کند. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | چند ارائهٔ PowerPoint با فرمت یکسان را در یک فایل ارائه ادغام می‌کند. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | چند ارائهٔ PowerPoint با فرمت یکسان را در یک فایل ارائه ادغام می‌کند. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | چند ارائهٔ PowerPoint با فرمت یکسان را در یک فایل ارائه ادغام می‌کند. |

### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

چند ارائهٔ PowerPoint با فرمت یکسان را در یک فایل ارائه ادغام می‌کند.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | یک آرایه از نام‌های فایل‌های ارائهٔ ورودی. |
| outputFileName | java.lang.String | نام فایل خروجی ارائهٔ ادغام‌شده. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

چند ارائهٔ PowerPoint با فرمت یکسان را در یک فایل ارائه ادغام می‌کند.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | یک آرایه از نام‌های فایل‌های ارائهٔ ورودی. |
| outputFileName | java.lang.String | نام فایل خروجی ارائهٔ ادغام‌شده. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های اضافه‌ای که نحوه ذخیرهٔ ارائهٔ ادغام‌شده را تعریف می‌کند. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

چند ارائهٔ PowerPoint با فرمت یکسان را در یک فایل ارائه ادغام می‌کند.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | یک آرایه از نام‌های فایل‌های ارائهٔ ورودی. |
| outputStream | java.io.OutputStream | جریان خروجی. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

چند ارائهٔ PowerPoint با فرمت یکسان را در یک فایل ارائه ادغام می‌کند.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | یک آرایه از نام‌های فایل‌های ارائهٔ ورودی. |
| outputStream | java.io.OutputStream | جریان خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های اضافه‌ای که نحوه ذخیرهٔ ارائهٔ ادغام‌شده را تعریف می‌کند. |