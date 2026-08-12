---
title: PresentationLockingBehavior
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แสดงพฤติกรรมการจัดการแหล่งข้อมูล IPresentation (ไฟล์หรือ System::IO::Stream) ระหว่างการโหลดและทำงานกับอินสแตนซ์ของ IPresentation."
type: docs
weight: 6748
url: /th/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

Represents the behavior regarding treating the [IPresentation](../ipresentation/) source (file or [System::IO::Stream](../../system.io/stream/)) while loading and working with an instance of [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| LoadAndRelease | 0 | แหล่งข้อมูลจะถูกล็อคเพียงช่วงเวลาที่การทำงานของคอนสตรัคเตอร์ [IPresentation](../ipresentation/) |
| KeepLocked | 1 | แหล่งข้อมูลจะถูกล็อคตลอดอายุการใช้งานของอ็อบเจ็กต์ [IPresentation](../ipresentation/) จนกว่าจะถูกทำลาย |

## หมายเหตุ

แหล่งข้อมูลเป็นพารามิเตอร์ที่ส่งให้กับคอนสตรัคเตอร์ [IPresentation](../ipresentation/) ในตัวอย่างด้านล่าง แหล่งข้อมูลคือไฟล์ "pres.pptx" :

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

สำหรับตัวอย่างนี้ แหล่งข้อมูล (ไฟล์ "pres.pptx") จะถูกล็อคตลอดอายุของอ็อบเจ็กต์ [IPresentation](../ipresentation/) ซึ่งหมายความว่าไม่สามารถเปลี่ยนแปลงหรือทำการลบโดยกระบวนการอื่นได้

## ดูเพิ่มเติม

* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)