---
title: Merger
second_title: مرجع API Aspose.Slides for Java
description: يمثل مجموعة من الطرق لدمج عروض PowerPoint التقديمية ذات التنسيق نفسه في ملف واحد.
type: docs
url: /ar/com.aspose.slides/merger/
---
**Inheritance:**
java.lang.Object
```
public class Merger
```

يمثل مجموعة من الطرق لدمج عروض PowerPoint التقديمية ذات التنسيق نفسه في ملف واحد.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | يدمج عدة عروض تقديمية PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | يدمج عدة عروض تقديمية PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | يدمج عدة عروض تقديمية PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | يدمج عدة عروض تقديمية PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


يدمج عدة عروض تقديمية PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | مصفوفة من أسماء ملفات العرض التقديمي المُدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج لملف العرض التقديمي المدمج الناتج. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


يدمج عدة عروض تقديمية PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | مصفوفة من أسماء ملفات العرض التقديمي المُدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج لملف العرض التقديمي المدمج الناتج. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | الخيارات الإضافية التي تحدد كيفية حفظ العرض التقديمي المدمج. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


يدمج عدة عروض تقديمية PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | مصفوفة من أسماء ملفات العرض التقديمي المُدخل. |
| outputStream | java.io.OutputStream | دفق الإخراج. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


يدمج عدة عروض تقديمية PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | مصفوفة من أسماء ملفات العرض التقديمي المُدخل. |
| outputStream | java.io.OutputStream | دفق الإخراج. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | الخيارات الإضافية التي تحدد كيفية حفظ العرض التقديمي المدمج. |