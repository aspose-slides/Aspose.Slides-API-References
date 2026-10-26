---
title: MarkdownExportType
second_title: Aspose.Slides para Android via Referência da API Java
description: Tipo de documento de renderização.
type: docs
url: /pt/com.aspose.slides/markdownexporttype/
---
**Herança:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Tipo de documento de renderização.

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

| Campo | Descrição |
| --- | --- |
| [Sequential](#Sequential) | Renderiza todos os itens separadamente. |
| [TextOnly](#TextOnly) | Renderiza apenas texto. |
| [Visual](#Visual) | Renderiza todos os itens, itens que são agrupados - renderizar juntos. |
### Sequential {#Sequential}
```
public static final int Sequential
```

Renderiza todos os itens separadamente. Um por um.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

Renderiza apenas texto.

### Visual {#Visual}
```
public static final int Visual
```

Renderiza todos os itens, itens que são agrupados - renderizar juntos.