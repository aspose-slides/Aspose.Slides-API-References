---
title: MarkdownExportType
second_title: Aspose.Slides voor Android via Java API-referentie
description: Type van renderend document.
type: docs
url: /nl/com.aspose.slides/markdownexporttype/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Type van renderend document.

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
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Sequential](#Sequential) | Render alle items afzonderlijk. |
| [TextOnly](#TextOnly) | Render alleen tekst. |
| [Visual](#Visual) | Render alle items, items die gegroepeerd zijn - render samen. |
### Sequential {#Sequential}
```
public static final int Sequential
```


Render alle items afzonderlijk. Eén voor één.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```


Render alleen tekst.

### Visual {#Visual}
```
public static final int Visual
```


Render alle items, items die gegroepeerd zijn - render samen.