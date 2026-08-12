---
title: get_RefreshThumbnail()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุว่าภาพย่อของงานนำเสนอจะถูกรีเฟรชหรือไม่. อ่าน bool. ค่าเริ่มต้นคือ true.
type: docs
weight: 53
url: /th/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() วิธีการ


ระบุว่า thumbnail ของการนำเสนอจะถูกรีเฟรชหรือไม่. อ่าน **bool**. ค่าเริ่มต้นคือ **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## หมายเหตุ


เมื่อค่าตัวเลือกเป็น **true**, thumbnail ใหม่จะถูกสร้างขึ้น.

เมื่อค่าตัวเลือกเป็น **false**, thumbnail ปัจจุบันจะถูกบันทึกไว้ตามเดิม.

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## ดูเพิ่มเติม

* คลาส [PptxOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)