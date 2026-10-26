---
title: MarkdownExportType
second_title: Aspose.Slides for Android ผ่านการอ้างอิง API ของ Java
description: ประเภทของเอกสารการแสดงผล.
type: docs
url: /th/com.aspose.slides/markdownexporttype/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MarkdownExportType extends System.Enum
```

ประเภทของเอกสารการแสดงผล.

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
| [Sequential](#Sequential) | แสดงผลทุกรายการแยกกัน |
| [TextOnly](#TextOnly) | แสดงเฉพาะข้อความเท่านั้น |
| [Visual](#Visual) | แสดงผลทุกรายการ, รายการที่จัดกลุ่มไว้ - แสดงร่วมกัน |
### Sequential {#Sequential}
```
public static final int Sequential
```


แสดงผลทุกรายการแยกกัน ทีละรายการ.

### TextOnly {#TextOnly}
```
public static final int TextOnly
```


แสดงเฉพาะข้อความเท่านั้น.

### Visual {#Visual}
```
public static final int Visual
```


แสดงผลทุกรายการ, รายการที่จัดกลุ่มไว้ - แสดงร่วมกัน.