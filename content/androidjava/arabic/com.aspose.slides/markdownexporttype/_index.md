---
title: MarkdownExportType
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: نوع مستند العرض.
type: docs
url: /ar/com.aspose.slides/markdownexporttype/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

نوع مستند العرض.

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
## الحقول

| الحقل | الوصف |
| --- | --- |
| [Sequential](#Sequential) | عرض جميع العناصر بشكل منفصل. |
| [TextOnly](#TextOnly) | عرض النص فقط. |
| [Visual](#Visual) | عرض جميع العناصر، والعناصر التي تم تجميعها - تُعرض معًا. |
### Sequential {#Sequential}
```
public static final int Sequential
```

عرض جميع العناصر بشكل منفصل. واحدًا تلو الآخر.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

عرض النص فقط.

### Visual {#Visual}
```
public static final int Visual
```

عرض جميع العناصر، والعناصر التي تم تجميعها - تُعرض معًا.