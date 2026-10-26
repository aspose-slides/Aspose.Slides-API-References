---
title: MarkdownExportType
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ประเภทของการเรนเดอร์เอกสาร.
type: docs
weight: 950
url: /th/aspose.slides.export/markdownexporttype/
---
## MarkdownExportType enum

ประเภทของการเรนเดอร์เอกสาร

```cpp
enum class MarkdownExportType
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| Sequential | 0 | เรนเดอร์ทุกรายการแยกจากกัน ทีละรายการ |
| TextOnly | 1 | เรนเดอร์เฉพาะข้อความเท่านั้น |
| Visual | 2 | เรนเดอร์ทุกรายการ รายการที่จัดกลุ่มกัน - เรนเดอร์พร้อมกัน |

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## ดูเพิ่มเติม

* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)