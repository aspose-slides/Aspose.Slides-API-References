---
title: MarkdownExportType
second_title: Aspose.Slides för Android via Java API-referens
description: Typ av renderingsdokument.
type: docs
url: /sv/com.aspose.slides/markdownexporttype/
---
**Arv:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Typ av renderingsdokument.

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

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Sequential](#Sequential) | Rendera alla objekt separat. |
| [TextOnly](#TextOnly) | Rendera endast text. |
| [Visual](#Visual) | Rendera alla objekt, objekt som är grupperade - rendera tillsammans. |
### Sekventiell {#Sequential}
```
public static final int Sequential
```


Rendera alla objekt separat. Ett i taget.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```


Rendera endast text.

### Visual {#Visual}
```
public static final int Visual
```


Rendera alla objekt, objekt som är grupperade - rendera tillsammans.