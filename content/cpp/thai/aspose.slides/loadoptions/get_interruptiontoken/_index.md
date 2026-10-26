---
title: get_InterruptionToken()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: โทเคนสำหรับตรวจสอบคำขอการขัดจังหวะ.
type: docs
weight: 235
url: /th/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() เมธอด

โทเคนสำหรับตรวจสอบคำขอการขัดจังหวะ

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## หมายเหตุ

โทเคนนี้จัดการช่วงอายุทั้งหมดของอินสแตนซ์ [IPresentation](../../ipresentation/). การดำเนินการที่ใช้เวลานานใด ๆ เช่น การโหลดหรือการบันทึกพรีเซนเทชัน จะถูกขัดจังหวะโดยการเรียกเมธอด [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) ของ [InterruptionTokenSource](../../interruptiontokensource/)

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInterruptionToken](../../iinterruptiontoken/)
* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)