---
title: MarkdownExportType
second_title: Aspose.Slides pro Java API Reference
description: Typ vykreslovacího dokumentu.
type: docs
url: /cs/com.aspose.slides/markdownexporttype/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Typ vykreslovacího dokumentu.

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
## Pole

| Field | Popis |
| --- | --- |
| [Sequential](#Sequential) | Vykresluje všechny položky samostatně. |
| [TextOnly](#TextOnly) | Vykresluje pouze text. |
| [Visual](#Visual) | Vykresluje všechny položky, položky, které jsou seskupeny - vykresluje je společně. |
### Sequential {#Sequential}
```
public static final int Sequential
```


Vykresluje všechny položky samostatně. Jednu po druhé.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```


Vykresluje pouze text.

### Visual {#Visual}
```
public static final int Visual
```


Vykresluje všechny položky, položky, které jsou seskupeny - vykresluje je společně.