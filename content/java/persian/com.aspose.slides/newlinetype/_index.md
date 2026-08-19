---
title: NewLineType
second_title: مرجع API Aspose.Slides برای Java
description: نوع خط جدیدی که در سند تولید شده استفاده خواهد شد.
type: docs
url: /fa/com.aspose.slides/newlinetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class NewLineType extends System.Enum
```

نوع خط جدیدی که در سند تولید شده استفاده خواهد شد.

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

## فیلدها

| فیلد | توضیح |
| --- | --- |
| [Windows](#Windows) |  |
| [Unix](#Unix) |  |
| [Mac](#Mac) | Mac (OS 9) خط جدید - \\\\r |
### ویندوز {#Windows}
```
public static final int Windows
```


### یونیکس {#Unix}
```
public static final int Unix
```


### مک {#Mac}
```
public static final int Mac
```


Mac (OS 9) خط جدید - \\\\r