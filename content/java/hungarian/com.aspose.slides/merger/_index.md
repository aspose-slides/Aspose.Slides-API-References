---
title: Merger
second_title: Aspose.Slides Java API hivatkozás
description: Csoport metódust képvisel a PowerPoint bemutatók azonos formátumban történő egyetlen fájlba egyesítéséhez.
type: docs
url: /hu/com.aspose.slides/merger/
---
**Öröklés:**
java.lang.Object
```
public class Merger
```

Egy csoport metódust képvisel a PowerPoint bemutatók azonos formátumban történő egyetlen fájlba egyesítéséhez.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Összevon több PowerPoint bemutatót azonos formátumban egyetlen bemutatófájlba. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Összevon több PowerPoint bemutatót azonos formátumban egyetlen bemutatófájlba. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Összevon több PowerPoint bemutatót azonos formátumban egyetlen bemutatófájlba. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Összevon több PowerPoint bemutatót azonos formátumban egyetlen bemutatófájlba. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


Összevon több PowerPoint bemutatót azonos formátumban egyetlen bemutatófájlba.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | A bemeneti bemutatófájlok neveit tartalmazó tömb. |
| outputFileName | java.lang.String | A keletkezett egyesített bemutatófájl kimeneti fájlneve. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


Összevon több PowerPoint bemutatót azonos formátumban egyetlen bemutatófájlba.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | A bemeneti bemutatófájlok neveit tartalmazó tömb. |
| outputFileName | java.lang.String | A keletkezett egyesített bemutatófájl kimeneti fájlneve. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Az extra beállítások, amelyek meghatározzák, hogyan kerül mentésre az egyesített bemutató. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


Összevon több PowerPoint bemutatót azonos formátumban egyetlen bemutatófájlba.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | A bemeneti bemutatófájlok neveit tartalmazó tömb. |
| outputStream | java.io.OutputStream | A kimeneti adatfolyam. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


Összevon több PowerPoint bemutatót azonos formátumban egyetlen bemutatófájlba.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | A bemeneti bemutatófájlok neveit tartalmazó tömb. |
| outputStream | java.io.OutputStream | A kimeneti adatfolyam. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Az extra beállítások, amelyek meghatározzák, hogyan kerül mentésre az egyesített bemutató. |