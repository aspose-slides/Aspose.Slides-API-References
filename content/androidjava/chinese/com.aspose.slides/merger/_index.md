---
title: Merger
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个用于将相同格式的 PowerPoint 演示文稿合并为一个文件的方法组。
type: docs
url: /zh/com.aspose.slides/merger/
---
**继承：**
java.lang.Object
```
public class Merger
```

表示一个用于将相同格式的 PowerPoint 演示文稿合并为一个文件的方法组。

## 方法

| 方法 | 描述 |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |

### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

将多个相同格式的 PowerPoint 演示文稿合并为单个演示文稿文件。

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

将多个相同格式的 PowerPoint 演示文稿合并为单个演示文稿文件。

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | 输入演示文稿文件名的数组。 |
| outputStream | java.io.OutputStream | 输出流。 |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 定义合并后演示文稿保存方式的附加选项。 |