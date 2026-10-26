---
title: MarkdownExportType
second_title: Aspose.Slides для Java – справочник API
description: Тип отображаемого документа.
type: docs
url: /ru/com.aspose.slides/markdownexporttype/
---
**Наследование:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Тип отображаемого документа.

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

## Поля

| Поле | Описание |
| --- | --- |
| [Sequential](#Sequential) | Отображать все элементы отдельно. |
| [TextOnly](#TextOnly) | Отображать только текст. |
| [Visual](#Visual) | Отображать все элементы, элементы, сгруппированные вместе, - отображать совместно. |
### Sequential {#Sequential}
```
public static final int Sequential
```

Отображать все элементы отдельно. По одному.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

Отображать только текст.

### Visual {#Visual}
```
public static final int Visual
```

Отображать все элементы, элементы, сгруппированные вместе, - отображать совместно.