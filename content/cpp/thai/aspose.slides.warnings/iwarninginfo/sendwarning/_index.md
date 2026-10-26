---
title: SendWarning()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: หาก receiver ไม่เป็น null จะจบการเตือนไปยัง receiver ที่ระบุและจะโยน AbortRequestedException หาก receiver ตัดสินใจยกเลิกการดำเนินการ.
type: docs
weight: 27
url: /th/aspose.slides.warnings/iwarninginfo/sendwarning/
---
## IWarningInfo::SendWarning(System::SharedPtr\<IWarningCallback\>) เมธอด

If receiver is not null ends warning to a specified receiver and throws the AbortRequestedException if receiver decided to abort a operation.

```cpp
virtual void Aspose::Slides::Warnings::IWarningInfo::SendWarning(System::SharedPtr<IWarningCallback> receiver)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| receiver | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningCallback](../../iwarningcallback/)\> | อ็อบเจกต์ผู้รับ [IWarningCallback](../../iwarningcallback/) |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IWarningCallback](../../iwarningcallback/)
* คลาส [IWarningInfo](../)
* เนมสเปซ [Aspose::Slides::Warnings](../../)
* Library [Aspose.Slides](../../../)