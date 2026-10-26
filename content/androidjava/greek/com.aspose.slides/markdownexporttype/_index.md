---
title: MarkdownExportType
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Τύπος εγγράφου απόδοσης.
type: docs
url: /el/com.aspose.slides/markdownexporttype/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Τύπος εγγράφου απόδοσης.

--------------------

> ```
> Example:
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
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Sequential](#Sequential) | Απεικονίζει όλα τα στοιχεία ξεχωριστά. |
| [TextOnly](#TextOnly) | Απεικονίζει μόνο το κείμενο. |
| [Visual](#Visual) | Απεικονίζει όλα τα στοιχεία, τα στοιχεία που είναι ομαδοποιημένα - απεικονίζονται μαζί. |
### Sequential {#Sequential}
```
public static final int Sequential
```

Απεικονίζει όλα τα στοιχεία ξεχωριστά. Ένα-ένα.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

Απεικονίζει μόνο το κείμενο.

### Visual {#Visual}
```
public static final int Visual
```

Απεικονίζει όλα τα στοιχεία, τα στοιχεία που είναι ομαδοποιημένα - απεικονίζονται μαζί.