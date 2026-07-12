---
title: MarkdownExportType
second_title: Aspose.Slides für Android über Java API Referenz
description: Typ des Renderdokuments.
type: docs
url: /de/com.aspose.slides/markdownexporttype/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Typ des Renderdokuments.

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

## Felder

| Feld | Beschreibung |
| --- | --- |
| [Sequential](#Sequential) | Rendert alle Elemente einzeln. |
| [TextOnly](#TextOnly) | Rendert nur Text. |
| [Visual](#Visual) | Rendert alle Elemente, gruppierte Elemente zusammen. |
### Sequential {#Sequential}
```
public static final int Sequential
```


Rendert alle Elemente einzeln. Eins nach dem anderen.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```


Rendert nur Text.

### Visual {#Visual}
```
public static final int Visual
```


Rendert alle Elemente, gruppierte Elemente zusammen.