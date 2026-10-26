---
title: Merger
second_title: Aspose.Slides for Android Java API referencia
description: A PowerPoint-bemutatók azonos formátumban egy fájlba egyesítésére szolgáló módszerek csoportját képviseli.
type: docs
url: /hu/com.aspose.slides/merger/
---
**Öröklés:**
java.lang.Object
```
public class Merger
```

A PowerPoint-bemutatók azonos formátumban egy fájlba egyesítésére szolgáló módszerek csoportját képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Több, azonos formátumú PowerPoint-bemutatót egyetlen bemutatófájlba egyesít. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Több, azonos formátumú PowerPoint-bemutatót egyetlen bemutatófájlba egyesít. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Több, azonos formátumú PowerPoint-bemutatót egyetlen bemutatófájlba egyesít. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Több, azonos formátumú PowerPoint-bemutatót egyetlen bemutatófájlba egyesít. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

Több, azonos formátumú PowerPoint-bemutatót egyetlen bemutatófájlba egyesít.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | A bemeneti bemutató fájlneveinek tömbje. |
| outputFileName | java.lang.String | A létrejövő egyesített bemutatófájl kimeneti fájlneve. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

Több, azonos formátumú PowerPoint-bemutatót egyetlen bemutatófájlba egyesít.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | A bemeneti bemutató fájlneveinek tömbje. |
| outputFileName | java.lang.String | A létrejövő egyesített bemutatófájl kimeneti fájlneve. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | A további beállítások, amelyek meghatározzák, hogyan kerül elmentésre az egyesített bemutató. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

Több, azonos formátumú PowerPoint-bemutatót egyetlen bemutatófájlba egyesít.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | A bemeneti bemutató fájlneveinek tömbje. |
| outputStream | java.io.OutputStream | A kimeneti adatfolyam. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

Több, azonos formátumú PowerPoint-bemutatót egyetlen bemutatófájlba egyesít.

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
| inputFileNames | java.lang.String[] | A bemeneti bemutató fájlneveinek tömbje. |
| outputStream | java.io.OutputStream | A kimeneti adatfolyam. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | A további beállítások, amelyek meghatározzák, hogyan kerül elmentésre az egyesített bemutató. |