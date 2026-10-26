---
title: Merger
second_title: Aspose.Slides для Java API Справочник
description: Представляет группу методов для объединения презентаций PowerPoint одного и того же формата в один файл.
type: docs
url: /ru/com.aspose.slides/merger/
---
**Наследование:**
java.lang.Object
```
public class Merger
```

Представляет группу методов для объединения презентаций PowerPoint одного и того же формата в один файл.

## Методы

| Метод | Описание |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Объединяет несколько презентаций PowerPoint одного и того же формата в один файл презентации. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Объединяет несколько презентаций PowerPoint одного и того же формата в один файл презентации. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Объединяет несколько презентаций PowerPoint одного и того же формата в один файл презентации. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Объединяет несколько презентаций PowerPoint одного и того же формата в один файл презентации. |

### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

Объединяет несколько презентаций PowerPoint одного и того же формата в один файл презентации.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Массив имён входных файлов презентаций. |
| outputFileName | java.lang.String | Имя выходного файла полученной объединённой презентации. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

Объединяет несколько презентаций PowerPoint одного и того же формата в один файл презентации.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Массив имён входных файлов презентаций. |
| outputFileName | java.lang.String | Имя выходного файла полученной объединённой презентации. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Дополнительные параметры, определяющие, как сохраняется объединённая презентация. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

Объединяет несколько презентаций PowerPoint одного и того же формата в один файл презентации.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Массив имён входных файлов презентаций. |
| outputStream | java.io.OutputStream | Поток вывода. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

Объединяет несколько презентаций PowerPoint одного и того же формата в один файл презентации.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Массив имён входных файлов презентаций. |
| outputStream | java.io.OutputStream | Поток вывода. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Дополнительные параметры, определяющие, как сохраняется объединённая презентация. |