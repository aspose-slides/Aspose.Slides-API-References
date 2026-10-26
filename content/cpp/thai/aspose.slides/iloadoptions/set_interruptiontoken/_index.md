---
title: set_InterruptionToken()
second_title: Aspose.Slides สำหรับ API Reference ของ C++
description: โทเค็นสำหรับตรวจสอบคำขอการหยุดทำงาน.
type: docs
weight: 248
url: /th/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) เมธอด

โทเค็นสำหรับตรวจสอบคำขอการหยุดทำงาน.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## หมายเหตุ

โทเค็นนี้จัดการอายุการใช้งานของอ็อบเจ็กต์ [IPresentation](../../ipresentation/) ทั้งหมด ทุกการทำงานที่ใช้เวลานาน เช่น การโหลดหรือการบันทึกการนำเสนอ จะถูกหยุดโดยการเรียก [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) เมธอด ของ [IInterruptionTokenSource](../../iinterruptiontokensource/).

## ดูเพิ่มเติม

* ชนิดนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IInterruptionToken](../../iinterruptiontoken/)
* คลาส [ILoadOptions](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)