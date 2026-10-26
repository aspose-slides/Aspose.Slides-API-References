---
title: MarkdownExportType
second_title: Aspose.Slides for Android 的 Java API 参考
description: 渲染文档的类型。
type: docs
url: /zh/com.aspose.slides/markdownexporttype/
---
**继承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

文档渲染类型。

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
## Fields

| Field | Description |
| --- | --- |
| [Sequential](#Sequential) | Render all items separately. |
| [TextOnly](#TextOnly) | Render only text. |
| [Visual](#Visual) | Render all items, items that are grouped - render together. |
### Sequential {#Sequential}
```
public static final int Sequential
```

Render all items separately. One by one.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

Render only text.

### Visual {#Visual}
```
public static final int Visual

Render all items, items that are grouped - render together.