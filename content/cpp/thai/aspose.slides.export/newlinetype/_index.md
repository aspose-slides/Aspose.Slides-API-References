---
title: NewLineType
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ประเภทของบรรทัดใหม่ที่จะใช้ในเอกสารที่สร้างขึ้น
type: docs
weight: 963
url: /th/aspose.slides.export/newlinetype/
---
## NewLineType enum

Type of new line that will be used in generated document.

```cpp
enum class NewLineType
```

### Values

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| Windows | 0 | บรรทัดใหม่ของ DOS & Windows OS - \r\n |
| Unix | 1 | บรรทัดใหม่ของ Unix & Mac OS X - \n |
| Mac | 2 | บรรทัดใหม่ของ Mac (OS 9) - \r |

## หมายเหตุ

ตัวอย่าง 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"doc.md", System::IO::FileMode::OpenOrCreate);

System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(stream, slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## ดูเพิ่มเติม

* เนมส페ซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)