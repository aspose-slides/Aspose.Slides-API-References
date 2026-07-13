---
title: MarkdownExportType
second_title: Aspose.Slides dla Androida za pośrednictwem dokumentacji API Java
description: Typ dokumentu renderującego.
type: docs
url: /pl/com.aspose.slides/markdownexporttype/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Typ dokumentu renderującego.

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
## Pola

| Pole | Opis |
| --- | --- |
| [Sequential](#Sequential) | Renderuj wszystkie elementy osobno. |
| [TextOnly](#TextOnly) | Renderuj tylko tekst. |
| [Visual](#Visual) | Renderuj wszystkie elementy, elementy zgrupowane – renderuj razem. |
### Sequential {#Sequential}
```
public static final int Sequential
```

Renderuj wszystkie elementy osobno. Jeden po drugim.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

Renderuj tylko tekst.

### Visual {#Visual}
```
public static final int Visual
```

Renderuj wszystkie elementy, elementy zgrupowane – renderuj razem.