---
title: MarkdownExportType
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Jenis dokumen rendering.
type: docs
url: /id/com.aspose.slides/markdownexporttype/
---
**Pewarisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

Jenis dokumen rendering.

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

## Bidang

| Field | Deskripsi |
| --- | --- |
| [Sequential](#Sequential) | Render semua item secara terpisah. |
| [TextOnly](#TextOnly) | Render hanya teks. |
| [Visual](#Visual) | Render semua item, item yang dikelompokkan - render bersama. |
### Sequential {#Sequential}
```
public static final int Sequential
```


Render semua item secara terpisah. Satu per satu.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```


Render hanya teks.

### Visual {#Visual}
```
public static final int Visual
```


Render semua item, item yang dikelompokkan - render bersama.