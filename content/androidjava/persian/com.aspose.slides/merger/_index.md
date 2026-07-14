---
title: Merger
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک گروه از متدها برای ادغام ارائه‌های PowerPoint با قالب یکسان در یک فایل است.
type: docs
url: /fa/com.aspose.slides/merger/
---
**ارث‌بری:**
java.lang.Object
```
public class Merger
```

نمایانگر یک گروه از متدها برای ادغام ارائه‌های PowerPoint با قالب یکسان در یک فایل است.
## متدها

| متد | توضیح |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | چندین ارائه PowerPoint با قالب یکسان را در یک فایل ارائه ترکیبی ادغام می‌کند. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | چندین ارائه PowerPoint با قالب یکسان را در یک فایل ارائه ترکیبی ادغام می‌کند. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | چندین ارائه PowerPoint با قالب یکسان را در یک فایل ارائه ترکیبی ادغام می‌کند. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | چندین ارائه PowerPoint با قالب یکسان را در یک فایل ارائه ترکیبی ادغام می‌کند. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

چندین ارائه PowerPoint با قالب یکسان را در یک فایل ارائه ترکیبی ادغام می‌کند.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | یک آرایه از نام‌های فایل‌های ارائه ورودی. |
| outputFileName | java.lang.String | نام فایل خروجی برای فایل ارائه ترکیبی حاصل. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

چندین ارائه PowerPoint با قالب یکسان را در یک فایل ارائه ترکیبی ادغام می‌کند.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | یک آرایه از نام‌های فایل‌های ارائه ورودی. |
| outputFileName | java.lang.String | نام فایل خروجی برای فایل ارائه ترکیبی حاصل. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های اضافی که نحوه ذخیره‌سازی ارائه ترکیبی را تعریف می‌کند. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

چندین ارائه PowerPoint با قالب یکسان را در یک فایل ارائه ترکیبی ادغام می‌کند.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | یک آرایه از نام‌های فایل‌های ارائه ورودی. |
| outputStream | java.io.OutputStream | جریان خروجی. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

چندین ارائه PowerPoint با قالب یکسان را در یک فایل ارائه ترکیبی ادغام می‌کند.

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
| inputFileNames | java.lang.String[] | یک آرایه از نام‌های فایل‌های ارائه ورودی. |
| outputStream | java.io.OutputStream | جریان خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های اضافی که نحوه ذخیره‌سازی ارائه ترکیبی را تعریف می‌کند. |