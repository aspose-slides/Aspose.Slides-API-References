---
title: set_InterruptionToken()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: โทเค็นที่ใช้ตรวจสอบการร้องขอการขัดจังหวะ.
type: docs
weight: 248
url: /th/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) เมธอด


โทเค็นที่ใช้ตรวจสอบการร้องขอการขัดจังหวะ.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## หมายเหตุ


โทเค็นนี้จัดการวงจรชีวิตของอินสแตนซ์ [IPresentation](../../ipresentation/) ทั้งหมด. ปฏิบัติการที่ใช้เวลานานใด ๆ เช่น การโหลดหรือการบันทึกของงานนำเสนอ จะถูกขัดจังหวะโดยการเรียก [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) เมธอด ของ [InterruptionTokenSource](../../interruptiontokensource/). 

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IInterruptionToken](../../iinterruptiontoken/)
* คลาส [LoadOptions](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)