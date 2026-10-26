---
title: NewLineType
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง API ของ Java
description: ประเภทของบรรทัดใหม่ที่จะใช้ในเอกสารที่สร้าง
type: docs
url: /th/com.aspose.slides/newlinetype/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class NewLineType extends System.Enum
```

ประเภทของบรรทัดใหม่ที่จะใช้ในเอกสารที่สร้าง

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
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [Windows](#Windows) |  |
| [Unix](#Unix) |  |
| [Mac](#Mac) |  |

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

Mac (OS 9) บรรทัดใหม่ - \\\\r