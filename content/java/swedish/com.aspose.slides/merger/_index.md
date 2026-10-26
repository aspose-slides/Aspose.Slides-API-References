---
title: Merger
second_title: Aspose.Slides för Java API-referens
description: Representerar en grupp metoder för att slå ihop PowerPoint-presentationer av samma format till en fil.
type: docs
url: /sv/com.aspose.slides/merger/
---
**Arv:**
java.lang.Object
```
public class Merger
```

Representerar en grupp metoder för att slå ihop PowerPoint-presentationer av samma format till en fil.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Slår ihop flera PowerPoint-presentationer av samma format till en enda presentationsfil. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Slår ihop flera PowerPoint-presentationer av samma format till en enda presentationsfil. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Slår ihop flera PowerPoint-presentationer av samma format till en enda presentationsfil. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Slår ihop flera PowerPoint-presentationer av samma format till en enda presentationsfil. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


Slår ihop flera PowerPoint-presentationer av samma format till en enda presentationsfil.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | En lista med namn på indata-presentationerna. |
| outputFileName | java.lang.String | Namnet på den utdatafil som den sammanslagna presentationen ska ha. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


Slår ihop flera PowerPoint-presentationer av samma format till en enda presentationsfil.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | En lista med namn på indata-presentationerna. |
| outputFileName | java.lang.String | Namnet på den utdatafil som den sammanslagna presentationen ska ha. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare alternativ som definierar hur den sammanslagna presentationen sparas. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


Slår ihop flera PowerPoint-presentationer av samma format till en enda presentationsfil.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | En lista med namn på indata-presentationerna. |
| outputStream | java.io.OutputStream | Utdataflödet. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


Slår ihop flera PowerPoint-presentationer av samma format till en enda presentationsfil.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | En lista med namn på indata-presentationerna. |
| outputStream | java.io.OutputStream | Utdataflödet. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare alternativ som definierar hur den sammanslagna presentationen sparas. |