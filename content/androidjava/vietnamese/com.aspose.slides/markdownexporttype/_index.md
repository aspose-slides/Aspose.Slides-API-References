---
title: MarkdownExportType
second_title: Tham khảo API Java Aspose.Slides cho Android
description: Loại tài liệu hiển thị.
type: docs
url: /vi/com.aspose.slides/markdownexporttype/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Loại tài liệu hiển thị.

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
## Các trường

| Trường | Mô tả |
| --- | --- |
| [Sequential](#Sequential) | Hiển thị từng mục riêng biệt. |
| [TextOnly](#TextOnly) | Chỉ hiển thị văn bản. |
| [Visual](#Visual) | Hiển thị tất cả các mục, các mục được nhóm - hiển thị cùng nhau. |
### Sequential {#Sequential}
```
public static final int Sequential
```

Hiển thị từng mục riêng biệt. Từng mục một.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

Chỉ hiển thị văn bản.

### Visual {#Visual}
```
public static final int Visual
```

Hiển thị tất cả các mục, các mục được nhóm - hiển thị cùng nhau.