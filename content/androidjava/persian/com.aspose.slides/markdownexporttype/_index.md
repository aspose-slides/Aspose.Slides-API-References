---
title: MarkdownExportType
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نوع سند رندرینگ.
type: docs
url: /fa/com.aspose.slides/markdownexporttype/
---
**وراثت:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

نوع سند رندرینگ.

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

## فیلدها

| فیلد | توضیح |
| --- | --- |
| [Sequential](#Sequential) | همه موارد را به صورت جداگانه رندر می‌کند. |
| [TextOnly](#TextOnly) | فقط متن را رندر می‌کند. |
| [Visual](#Visual) | همه موارد، موارد گروه‌بندی شده - به‌صورت مشترک رندر می‌شوند. |
### Sequential {#Sequential}
```
public static final int Sequential
```

همه موارد را به‌صورت جداگانه رندر می‌کند. یکی‌یکی.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

فقط متن را رندر می‌کند.

### Visual {#Visual}
```
public static final int Visual
```

همه موارد، موارد گروه‌بندی شده - به‌صورت مشترک رندر می‌شوند.