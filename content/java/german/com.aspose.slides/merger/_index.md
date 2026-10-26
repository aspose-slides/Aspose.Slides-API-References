---
title: Merger
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Gruppe von Methoden zum Zusammenführen von PowerPoint-Präsentationen desselben Formats in einer Datei dar.
type: docs
url: /de/com.aspose.slides/merger/
---
**Vererbung:**
java.lang.Object
```
public class Merger
```

Stellt eine Gruppe von Methoden zum Zusammenführen von PowerPoint-Präsentationen desselben Formats in einer Datei dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzigen Präsentationsdatei zusammen.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | An array of the input presentation file names. |
| outputFileName | java.lang.String | The output file name of the resulting merged presentation file. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzigen Präsentationsdatei zusammen.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | An array of the input presentation file names. |
| outputFileName | java.lang.String | The output file name of the resulting merged presentation file. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | The additional options that define how the merged presentation is saved. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzigen Präsentationsdatei zusammen.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | An array of the input presentation file names. |
| outputStream | java.io.OutputStream | The output stream. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzigen Präsentationsdatei zusammen.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | An array of the input presentation file names. |
| outputStream | java.io.OutputStream | The output stream. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | The additional options that define how the merged presentation is saved. |