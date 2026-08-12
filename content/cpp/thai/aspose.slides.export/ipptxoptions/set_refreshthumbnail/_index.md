---
title: set_RefreshThumbnail()
second_title: อ้างอิง API ของ Aspose.Slides for C++
description: ระบุว่าภาพย่อของงานนำเสนอจะได้รับการรีเฟรชหรือไม่ เขียน bool ค่าเริ่มต้นคือ true.
type: docs
weight: 66
url: /th/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) method

ระบุว่าภาพย่อของงานนำเสนอจะได้รับการรีเฟรชหรือไม่ เขียน **bool**. ค่าเริ่มต้นคือ **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## Remarks

เมื่อค่าตัวเลือกเป็น **true** ภาพย่อใหม่จะถูกสร้างขึ้น

เมื่อค่าตัวเลือกเป็น **false** ภาพย่อปัจจุบันจะถูกบันทึกตามเดิม

Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## See Also

* Class [IPptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)