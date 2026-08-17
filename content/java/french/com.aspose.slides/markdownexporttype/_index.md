---
title: MarkdownExportType
second_title: Référence de l'API Aspose.Slides pour Java
description: Type de document de rendu.
type: docs
url: /fr/com.aspose.slides/markdownexporttype/
---
**Héritage:** 
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Type de document de rendu.

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
## Champs

| Champ | Description |
| --- | --- |
| [Sequential](#Sequential) | Rendre tous les éléments séparément. |
| [TextOnly](#TextOnly) | Rendre uniquement le texte. |
| [Visual](#Visual) | Rendre tous les éléments, les éléments groupés - rendre ensemble. |
### Sequential {#Sequential}
```
public static final int Sequential
```


Rendre tous les éléments séparément. Un par un.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```


Rendre uniquement le texte.

### Visual {#Visual}
```
public static final int Visual
```