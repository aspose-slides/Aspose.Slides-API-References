---
title: Merger
second_title: Référence API Aspose.Slides pour Java
description: Représente un groupe de méthodes permettant de fusionner des présentations PowerPoint du même format en un seul fichier.
type: docs
url: /fr/com.aspose.slides/merger/
---
**Héritage :**
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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Un tableau des noms de fichiers de présentation d'entrée. |
| outputFileName | java.lang.String | Le nom du fichier de sortie de la présentation fusionnée résultante. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

Fusionne plusieurs présentations PowerPoint du même format en un seul fichier de présentation.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Un tableau des noms de fichiers de présentation d'entrée. |
| outputFileName | java.lang.String | Le nom du fichier de sortie de la présentation fusionnée résultante. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Les options supplémentaires qui définissent comment la présentation fusionnée est enregistrée. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

Fusionne plusieurs présentations PowerPoint du même format en un seul fichier de présentation.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Un tableau des noms de fichiers de présentation d'entrée. |
| outputStream | java.io.OutputStream | Le flux de sortie. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

Fusionne plusieurs présentations PowerPoint du même format en un seul fichier de présentation.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Un tableau des noms de fichiers de présentation d'entrée. |
| outputStream | java.io.OutputStream | Le flux de sortie. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Les options supplémentaires qui définissent comment la présentation fusionnée est enregistrée. |