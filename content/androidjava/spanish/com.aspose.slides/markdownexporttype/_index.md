---
title: MarkdownExportType
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Tipo de documento de renderizado.
type: docs
url: /es/com.aspose.slides/markdownexporttype/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Tipo de documento de renderizado.

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

## Campos

| Campo | Descripción |
| --- | --- |
| [Sequential](#Sequential) | Renderiza todos los elementos por separado. |
| [TextOnly](#TextOnly) | Renderiza solo texto. |
| [Visual](#Visual) | Renderiza todos los elementos; los elementos agrupados se renderizan juntos. |
### Sequential {#Sequential}
```
public static final int Sequential
```


Renderiza todos los elementos por separado. Uno a uno.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```


Renderiza solo texto.

### Visual {#Visual}
```
public static final int Visual
```


Renderiza todos los elementos; los elementos agrupados se renderizan juntos.