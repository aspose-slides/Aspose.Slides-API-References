---
title: MarkdownExportType
second_title: Aspose.Slides for Java API 参考
description: 文档的渲染类型。
type: docs
url: /zh/com.aspose.slides/markdownexporttype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

文档的渲染类型。

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
## 字段

| 字段 | 描述 |
| --- | --- |
| [Sequential](#Sequential) | 分别渲染所有项。 |
| [TextOnly](#TextOnly) | 仅渲染文本。 |
| [Visual](#Visual) | 渲染所有项，分组的项一起渲染。 |
### Sequential {#Sequential}
```
public static final int Sequential
```

分别渲染所有项。一次一个。

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

仅渲染文本。

### Visual {#Visual}
```
public static final int Visual
```

渲染所有项，分组的项一起渲染。