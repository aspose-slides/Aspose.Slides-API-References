---
title: NewLineType
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: نوع سطر جديد سيتم استخدامه في المستند المُولَّد.
type: docs
url: /ar/com.aspose.slides/newlinetype/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class NewLineType extends System.Enum
```

نوع سطر جديد سيتم استخدامه في المستند المُولَّد.

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

## الحقول

| الحقل | الوصف |
| --- | --- |
| [Windows](#Windows) |  |
| [Unix](#Unix) |  |
| [Mac](#Mac) | ماك (OS 9) سطر جديد - \\r |
### ويندوز {#Windows}
```
public static final int Windows
```

### يونكس {#Unix}
```
public static final int Unix
```

### ماك {#Mac}
```
public static final int Mac
```

ماك (OS 9) سطر جديد - \\r