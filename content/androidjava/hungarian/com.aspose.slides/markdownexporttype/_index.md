---
title: MarkdownExportType
second_title: Aspose.Slides Androidra a Java API Referencián keresztül
description: A dokumentum renderelésének típusa.
type: docs
url: /hu/com.aspose.slides/markdownexporttype/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

A dokumentum renderelésének típusa.

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

## Mezők

| Mező | Leírás |
| --- | --- |
| [Sequential](#Sequential) | Az összes elemet külön-külön rendereli. |
| [TextOnly](#TextOnly) | Csak a szöveget rendereli. |
| [Visual](#Visual) | Az összes elemet, a csoportosított elemeket együtt rendereli. |
### Soros {#Sequential}
```
public static final int Sequential
```

Az összes elemet külön-külön rendereli, egyesével.

### CsakSzöveg {#TextOnly}
```
public static final int TextOnly
```

Csak a szöveget rendereli.

### Vizuális {#Visual}
```
public static final int Visual
```

Az összes elemet, a csoportosított elemeket együtt rendereli.