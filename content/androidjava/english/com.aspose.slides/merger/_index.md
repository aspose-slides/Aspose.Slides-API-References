---
title: Merger
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a group of methods for merging PowerPoint presentations of the same format into one file.
type: docs
url: /com.aspose.slides/merger/
---
**Inheritance:**
java.lang.Object
```
public class Merger
```

Represents a group of methods for merging PowerPoint presentations of the same format into one file.
## Methods

| Method | Description |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


Merges multiple PowerPoint presentations of the same format into a single presentation file.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | An array of the input presentation file names. |
| outputFileName | java.lang.String | The output file name of the resulting merged presentation file. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


Merges multiple PowerPoint presentations of the same format into a single presentation file.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | An array of the input presentation file names. |
| outputFileName | java.lang.String | The output file name of the resulting merged presentation file. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | The additional options that define how the merged presentation is saved. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


Merges multiple PowerPoint presentations of the same format into a single presentation file.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | An array of the input presentation file names. |
| outputStream | java.io.OutputStream | The output stream. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


Merges multiple PowerPoint presentations of the same format into a single presentation file.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | An array of the input presentation file names. |
| outputStream | java.io.OutputStream | The output stream. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | The additional options that define how the merged presentation is saved. |

