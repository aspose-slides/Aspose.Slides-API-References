---
title: MarkdownExportType
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ประเภทของเอกสารการแสดงผล
type: docs
url: /th/com.aspose.slides/markdownexporttype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

ประเภทของเอกสารการแสดงผล

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
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [Sequential](#Sequential) | เรนเดอร์ทุกรายการแยกกัน |
| [TextOnly](#TextOnly) | เรนเดอร์เฉพาะข้อความ |
| [Visual](#Visual) | เรนเดอร์ทุกรายการ, รายการที่จัดกลุ่มกัน - เรนเดอร์รวมกัน |
### ต่อเนื่อง {#Sequential}
```
public static final int Sequential
```

เรนเดอร์ทุกรายการแยกกัน ทีละหนึ่งรายการ.

### ข้อความเท่านั้น {#TextOnly}
```
public static final int TextOnly
```

เรนเดอร์เฉพาะข้อความ.

### ภาพ {#Visual}
```
public static final int Visual
```

เรนเดอร์ทุกรายการ, รายการที่จัดกลุ่มกัน - เรนเดอร์รวมกัน.