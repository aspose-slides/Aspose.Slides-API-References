---
title: MarkdownExportType
second_title: Aspose.Slides für Java API-Referenz
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
| [Sequential](#Sequential) | Render all items separately. |
| [TextOnly](#TextOnly) | Render only text. |
| [Visual](#Visual) | Render all items, items that are grouped - render together. |
### Sequential {#Sequential}
```
public static final int Sequential
```

Alle Elemente einzeln rendern. Eins nach dem anderen.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

Nur Text rendern.

### Visual {#Visual}
```
public static final int Visual
```

Alle Elemente rendern, gruppierte Elemente zusammen rendern.