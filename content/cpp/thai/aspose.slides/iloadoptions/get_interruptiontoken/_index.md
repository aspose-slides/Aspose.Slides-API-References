---
title: get_InterruptionToken()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: โทเค็นสำหรับตรวจสอบคำขอการขัดจังหวะ.
type: docs
weight: 235
url: /th/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() เมธอด


โทเค็นสำหรับตรวจสอบคำขอการขัดจังหวะ.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## หมายเหตุ


โทเค็นนี้จัดการอายุการใช้งานของอินสแทนซ์ [IPresentation](../../ipresentation/) ทั้งหมด. การดำเนินการที่ใช้เวลานานใด ๆ เช่น การโหลดหรือบันทึกการนำเสนอ, จะถูกขัดจังหวะโดยการเรียกใช้ [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) เมธอดของ [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IInterruptionToken](../../iinterruptiontoken/)
* คลาส [ILoadOptions](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)