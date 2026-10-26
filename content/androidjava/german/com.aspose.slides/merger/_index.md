---
title: Merger
second_title: Aspose.Slides für Android via Java API-Referenz
description: Stellt eine Gruppe von Methoden zum Zusammenführen von PowerPoint-Präsentationen desselben Formats in einer einzigen Datei dar.
type: docs
url: /de/com.aspose.slides/merger/
---
**Vererbung:**
java.lang.Object
```
public class Merger
```

Stellt eine Gruppe von Methoden zum Zusammenführen von PowerPoint-Präsentationen desselben Formats in eine Datei dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzelnen Präsentationsdatei zusammen. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzelnen Präsentationsdatei zusammen. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzelnen Präsentationsdatei zusammen. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzelnen Präsentationsdatei zusammen. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzelnen Präsentationsdatei zusammen.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Ein Array mit den Dateinamen der Eingabepräsentationen. |
| outputFileName | java.lang.String | Der Ausgabedateiname der resultierenden zusammengeführten Präsentationsdatei. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzelnen Präsentationsdatei zusammen.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Ein Array mit den Dateinamen der Eingabepräsentationen. |
| outputFileName | java.lang.String | Der Ausgabedateiname der resultierenden zusammengeführten Präsentationsdatei. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Die zusätzlichen Optionen, die festlegen, wie die zusammengeführte Präsentation gespeichert wird. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzelnen Präsentationsdatei zusammen.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Ein Array mit den Dateinamen der Eingabepräsentationen. |
| outputStream | java.io.OutputStream | Der Ausgabestream. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


Führt mehrere PowerPoint-Präsentationen desselben Formats zu einer einzelnen Präsentationsdatei zusammen.

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
| inputFileNames | java.lang.String[] | Ein Array mit den Dateinamen der Eingabepräsentationen. |
| outputStream | java.io.OutputStream | Der Ausgabestream. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Die zusätzlichen Optionen, die festlegen, wie die zusammengeführte Präsentation gespeichert wird. |