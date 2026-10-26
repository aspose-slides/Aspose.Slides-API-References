---
title: MarkdownExportType
second_title: Aspose.Slides for Java API 參考文件
description: 文件的渲染類型。
type: docs
url: /zh-hant/com.aspose.slides/markdownexporttype/
---
**繼承關係:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

文件的渲染類型。

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

## 欄位

| 欄位 | 說明 |
| --- | --- |
| [Sequential](#Sequential) | 分別渲染所有項目。 |
| [TextOnly](#TextOnly) | 僅渲染文字。 |
| [Visual](#Visual) | 渲染所有項目，若項目已分組則一起渲染。 |
### Sequential {#Sequential}
```
public static final int Sequential
```

分別渲染所有項目。一次一個。

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

僅渲染文字。

### Visual {#Visual}
```
public static final int Visual
```

渲染所有項目，若項目已分組則一起渲染。