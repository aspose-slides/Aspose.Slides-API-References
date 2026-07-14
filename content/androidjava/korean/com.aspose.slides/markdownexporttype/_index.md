---
title: MarkdownExportType
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 문서 렌더링 유형.
type: docs
url: /ko/com.aspose.slides/markdownexporttype/
---
**상속:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

문서 렌더링 유형.

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
## 필드

| 필드 | 설명 |
| --- | --- |
| [Sequential](#Sequential) | 모든 항목을 개별적으로 렌더링합니다. |
| [TextOnly](#TextOnly) | 텍스트만 렌더링합니다. |
| [Visual](#Visual) | 모든 항목을 렌더링하고, 그룹화된 항목은 함께 렌더링합니다. |
### Sequential {#Sequential}
```
public static final int Sequential
```

모든 항목을 개별적으로, 하나씩 렌더링합니다.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

텍스트만 렌더링합니다.

### Visual {#Visual}
```
public static final int Visual
```

모든 항목을 렌더링하고, 그룹화된 항목은 함께 렌더링합니다.