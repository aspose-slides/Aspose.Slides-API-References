---
title: Merger
second_title: Aspose.Slides для Android через справочник Java API
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
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
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
| inputFileNames | java.lang.String[] | Массив имен входных файлов презентаций. |
| outputFileName | java.lang.String | Имя выходного файла результирующей объединённой презентации. |

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
| inputFileNames | java.lang.String[] | Массив имен входных файлов презентаций. |
| outputFileName | java.lang.String | Имя выходного файла результирующей объединённой презентации. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Дополнительные параметры, определяющие способ сохранения объединённой презентации. |

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
| inputFileNames | java.lang.String[] | Массив имен входных файлов презентаций. |
| outputStream | java.io.OutputStream | Выходной поток. |

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
| inputFileNames | java.lang.String[] | Массив имен входных файлов презентаций. |
| outputStream | java.io.OutputStream | Выходной поток. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Дополнительные параметры, определяющие способ сохранения объединённой презентации. |