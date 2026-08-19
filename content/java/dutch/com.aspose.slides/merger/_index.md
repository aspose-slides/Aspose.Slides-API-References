---
title: Merger
second_title: Aspose.Slides voor Java API Referentie
description: Stelt een groep methoden voor voor het samenvoegen van PowerPoint-presentaties van hetzelfde formaat tot één bestand.
type: docs
url: /nl/com.aspose.slides/merger/
---
**Inheritance:**
java.lang.Object
```
public class Merger
```

Stelt een groep methoden voor voor het samenvoegen van PowerPoint-presentaties van hetzelfde formaat tot één bestand.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatie-bestand. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatie-bestand. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatie-bestand. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatie-bestand. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatie-bestand.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Een array met de bestandsnamen van de invoerpresentaties. |
| outputFileName | java.lang.String | De bestandsnaam van het resulterende samengevoegde presentatie-bestand. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatie-bestand.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Een array met de bestandsnamen van de invoerpresentaties. |
| outputFileName | java.lang.String | De bestandsnaam van het resulterende samengevoegde presentatie-bestand. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | De extra opties die bepalen hoe de samengevoegde presentatie wordt opgeslagen. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatie-bestand.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Een array met de bestandsnamen van de invoerpresentaties. |
| outputStream | java.io.OutputStream | De uitvoerstroom. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatie-bestand.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Een array met de bestandsnamen van de invoerpresentaties. |
| outputStream | java.io.OutputStream | De uitvoerstroom. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | De extra opties die bepalen hoe de samengevoegde presentatie wordt opgeslagen. |