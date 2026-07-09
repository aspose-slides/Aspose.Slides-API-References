---
title: Merger
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un groupe de méthodes permettant de fusionner des présentations PowerPoint du même format en un seul fichier.
type: docs
url: /fr/com.aspose.slides/merger/
---
**Héritage:** 
java.lang.Object
```
public class Merger
```

Représente un groupe de méthodes permettant de fusionner des présentations PowerPoint du même format en un seul fichier.
## Méthodes

| Méthode | Description |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Fusionne plusieurs présentations PowerPoint du même format en un seul fichier de présentation. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Fusionne plusieurs présentations PowerPoint du même format en un seul fichier de présentation. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Fusionne plusieurs présentations PowerPoint du même format en un seul fichier de présentation. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Fusionne plusieurs présentations PowerPoint du même format en un seul fichier de présentation. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


Fusionne plusieurs présentations PowerPoint du même format en un seul fichier de présentation.

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


Fusionne plusieurs présentations PowerPoint du même format en un seul fichier de présentation.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Un tableau contenant les noms des fichiers de présentation d’entrée. |
| outputStream | java.io.OutputStream | Le flux de sortie. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Les options supplémentaires qui définissent comment la présentation fusionnée est enregistrée. |