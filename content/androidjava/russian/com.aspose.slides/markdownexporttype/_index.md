---
title: MarkdownExportType
second_title: Aspose.Slides для Android через справочник Java API
description: Тип документа рендеринга.
type: docs
url: /ru/com.aspose.slides/markdownexporttype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Тип документа рендеринга.

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
| [Sequential](#Sequential) | Отрисовывать все элементы по отдельности. |
| [TextOnly](#TextOnly) | Отрисовывать только текст. |
| [Visual](#Visual) | Отрисовывать все элементы, а элементы, которые сгруппированы, — отрисовывать вместе. |
### Sequential {#Sequential}
```
public static final int Sequential
```

Отрисовывать все элементы по отдельности. По одному.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

Отрисовывать только текст.

### Visual {#Visual}
```
public static final int Visual
```

Отрисовывать все элементы, а элементы, которые сгруппированы, — отрисовывать вместе.