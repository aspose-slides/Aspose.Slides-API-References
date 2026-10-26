---
title: set_RefreshThumbnail()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ระบุว่ารูปย่อของการนำเสนอจะถูกรีเฟรชหรือไม่ เขียนเป็น bool ค่าเริ่มต้นคือ true.
type: docs
weight: 66
url: /th/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) เมธอด

ระบุว่ารูปย่อของการนำเสนอจะถูกรีเฟรชหรือไม่ เขียนเป็น **bool** ค่าเริ่มต้นคือ **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## หมายเหตุ

เมื่อค่าตัวเลือกเป็น **true** รูปย่อใหม่จะถูกสร้างขึ้น.

เมื่อค่าตัวเลือกเป็น **false** รูปย่อปัจจุบันจะถูกบันทึกไว้ตามเดิม.

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