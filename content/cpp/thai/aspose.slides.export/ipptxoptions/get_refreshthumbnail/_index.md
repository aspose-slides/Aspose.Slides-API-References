---
title: get_RefreshThumbnail()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุว่ารูปย่อของงานนำเสนอจะถูกรีเฟรชหรือไม่. อ่าน bool. ค่าเริ่มต้นคือ true.
type: docs
weight: 53
url: /th/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() เมธอด


ระบุว่ารูปย่อของงานนำเสนอจะถูกรีเฟรชหรือไม่. อ่าน **bool**. ค่าเริ่มต้นคือ **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## หมายเหตุ


เมื่อค่าตัวเลือกเป็น **true**, รูปย่อใหม่จะถูกสร้างขึ้น.

เมื่อค่าตัวเลือกเป็น **false**, รูปย่อปัจจุบันจะถูกบันทึกตามเดิม.

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## ดูเพิ่มเติม

* คลาส [IPptxOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)