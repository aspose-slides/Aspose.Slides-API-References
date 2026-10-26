---
title: MarkdownExportType
second_title: Riferimento API di Aspose.Slides per Java
description: Tipo di documento di rendering.
type: docs
url: /it/com.aspose.slides/markdownexporttype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Tipo di documento di rendering.

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
## Campi

| Campo | Descrizione |
| --- | --- |
| [Sequential](#Sequential) | Renderizza tutti gli elementi separatamente. |
| [TextOnly](#TextOnly) | Renderizza solo il testo. |
| [Visual](#Visual) | Renderizza tutti gli elementi, gli elementi raggruppati - renderizza insieme. |
### Sequential {#Sequential}
```
public static final int Sequential
```

Renderizza tutti gli elementi separatamente. Uno per volta.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

Renderizza solo il testo.

### Visual {#Visual}
```
public static final int Visual
```

Renderizza tutti gli elementi, gli elementi raggruppati - renderizza insieme.