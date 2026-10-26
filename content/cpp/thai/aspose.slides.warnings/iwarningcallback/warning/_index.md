---
title: Warning()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: เมธอด callback ที่รับคำเตือนและตัดสินใจว่าการดำเนินการควรจะถูกยกเลิกหรือไม่.
type: docs
weight: 1
url: /th/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) เมธอด

เมธอด callback ที่รับคำเตือนและตัดสินใจว่าการดำเนินการควรจะถูกยกเลิกหรือไม่.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | คำเตือนที่จะประมวลผล. |

### ค่าที่คืน

การตัดสินใจยกเลิก [ReturnAction](../../returnaction/).

## ดูเพิ่มเติม

* Enum [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IWarningInfo](../../iwarninginfo/)
* คลาส [IWarningCallback](../)
* เนมสเปซ [Aspose::Slides::Warnings](../../)
* Library [Aspose.Slides](../../../)