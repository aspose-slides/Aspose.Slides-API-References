---
title: LoadExternalFonts()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เพิ่มโฟลเดอร์เพิ่มเติมเพื่อค้นหาแบบอักษร.
type: docs
weight: 1
url: /th/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) method

เพิ่มโฟลเดอร์เพิ่มเติมเพื่อค้นหาแบบอักษร.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | ไดเรกทอรีเพื่ออ่านแบบอักษรเพิ่มเติม. |
## หมายเหตุ



ตัวอย่างต่อไปนี้แสดงวิธีโหลดแบบอักษรที่กำหนดเองจากไฟล์ .TTF 
```cpp
// เส้นทางไปยังไดเรกทอรีเอกสาร.
System::String dataDir = u"C:\\";

// โฟลเดอร์เพื่อค้นหาแบบอักษร
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// โหลดแบบอักษรจากไดเรกทอรีแบบอักษรกำหนดเอง
FontsLoader::LoadExternalFonts(folders);

// ทำงานบางอย่างและทำการเรนเดอร์การนำเสนอ/สไลด์
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// ล้างแคชแบบอักษร
FontsLoader::ClearCache();
```

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [FontsLoader](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)