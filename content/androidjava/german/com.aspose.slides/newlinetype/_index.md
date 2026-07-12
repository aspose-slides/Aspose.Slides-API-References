---
title: NewLineType
second_title: Aspose.Slides für Android über Java API Referenz
description: Typ des Zeilenumbruchs, der im erzeugten Dokument verwendet wird.
type: docs
url: /de/com.aspose.slides/newlinetype/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class NewLineType extends System.Enum
```

Typ des Zeilenumbruchs, der im erzeugten Dokument verwendet wird.

--------------------

> ```
> Example
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Windows](#Windows) |  |
| [Unix](#Unix) |  |
| [Mac](#Mac) | Mac (OS 9) Zeilenumbruch - \\\\r |
### Windows {#Windows}
```
public static final int Windows
```


### Unix {#Unix}
```
public static final int Unix
```


### Mac {#Mac}
```
public static final int Mac
```


Mac (OS 9) Zeilenumbruch - \\\\r