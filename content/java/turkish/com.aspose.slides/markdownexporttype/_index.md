---
title: MarkdownExportType
second_title: Aspose.Slides for Java API Referansı
description: Belge görüntüleme türü.
type: docs
url: /tr/com.aspose.slides/markdownexporttype/
---
**Kalıtım:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Belge görüntüleme türü.

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
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Sequential](#Sequential) | Tüm öğeleri ayrı ayrı oluştur. |
| [TextOnly](#TextOnly) | Yalnızca metni oluştur. |
| [Visual](#Visual) | Tüm öğeleri oluştur, gruplanmış öğeler birlikte oluşturulsun. |
### Sequential {#Sequential}
```
public static final int Sequential
```

Tüm öğeleri ayrı ayrı, birer birer oluştur.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```

Yalnızca metni oluştur.

### Visual {#Visual}
```
public static final int Visual
```

Tüm öğeleri oluştur, gruplanmış öğeler birlikte oluşturulsun.