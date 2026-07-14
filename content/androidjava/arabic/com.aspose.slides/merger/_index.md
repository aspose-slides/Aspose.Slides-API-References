---
title: Merger
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من الأساليب لدمج عروض PowerPoint ذات الصيغة نفسها في ملف واحد.
type: docs
url: /ar/com.aspose.slides/merger/
---
**الوراثة:**  
java.lang.Object  
```
public class Merger
```

يمثل مجموعة من الطرق لدمج عروض PowerPoint ذات الصيغة نفسها في ملف واحد.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | يدمج عدة عروض PowerPoint ذات الصيغة نفسها في ملف عرض واحد. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | يدمج عدة عروض PowerPoint ذات الصيغة نفسها في ملف عرض واحد. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | يدمج عدة عروض PowerPoint ذات الصيغة نفسها في ملف عرض واحد. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | يدمج عدة عروض PowerPoint ذات الصيغة نفسها في ملف عرض واحد. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

يدمج عدة عروض PowerPoint ذات الصيغة نفسها في ملف عرض واحد.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | مصفوفة من أسماء ملفات العرض الإدخالية. |
| outputFileName | java.lang.String | اسم ملف الإخراج للعرض المدمج الناتج. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

يدمج عدة عروض PowerPoint ذات الصيغة نفسها في ملف عرض واحد.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | مصفوفة من أسماء ملفات العرض الإدخالية. |
| outputFileName | java.lang.String | اسم ملف الإخراج للعرض المدمج الناتج. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | الخيارات الإضافية التي تحدد كيفية حفظ العرض المدمج. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

يدمج عدة عروض PowerPoint ذات الصيغة نفسها في ملف عرض واحد.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | مصفوفة من أسماء ملفات العرض الإدخالية. |
| outputStream | java.io.OutputStream | دفق الإخراج. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

يدمج عدة عروض PowerPoint ذات الصيغة نفسها في ملف عرض واحد.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | مصفوفة من أسماء ملفات العرض الإدخالية. |
| outputStream | java.io.OutputStream | دفق الإخراج. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | الخيارات الإضافية التي تحدد كيفية حفظ العرض المدمج. |