---
title: NewLineType
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 생성된 문서에 사용될 새 줄 유형입니다.
type: docs
url: /ko/com.aspose.slides/newlinetype/
---
**상속:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class NewLineType extends System.Enum
```

생성된 문서에 사용될 새 줄 유형입니다.

--------------------

> ```
> Example
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
| [Windows](#Windows) |  |
| [Unix](#Unix) |  |
| [Mac](#Mac) | Mac (OS 9) 새 줄 - \\\\r |
### Windows {#Windows}
```
public static final int Windows
```


### Unix {#Unix}
```
public static final int Unix
```


### Mac {#Mac}
```
public static final int Mac
```


Mac (OS 9) 새 줄 - \\\\r