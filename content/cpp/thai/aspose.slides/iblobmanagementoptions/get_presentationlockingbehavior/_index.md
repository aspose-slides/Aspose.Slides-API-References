---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส Presentation สามารถเป็นเจ้าของแหล่งข้อมูล - ไฟล์หรือสตรีม ได้ตลอดอายุการใช้งานของตัวอย่างหรือไม่ หากตัวอย่างเป็นเจ้าของ จะทำการล็อคแหล่งข้อมูล สิ่งนี้ช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งข้อมูล (สตรีมหรือไฟล์) ไม่สามารถเปลี่ยนแปลงได้ตลอดอายุการใช้งานของ Presentation นี้เป็นตัวอย่าง:"
type: docs
weight: 1
url: /th/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() เมธอด

คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส [Presentation](../../presentation/) สามารถเป็นเจ้าของแหล่งข้อมูล - ไฟล์หรือสตรีม ระหว่างอายุการใช้งานของตัวอย่างได้หรือไม่. หากตัวอย่างเป็นเจ้าของ จะทำการล็อคแหล่งข้อมูล. สิ่งนี้ช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งข้อมูล (stream หรือ file) ไม่สามารถเปลี่ยนแปลงได้ระหว่างอายุการใช้งานของ [Presentation](../../presentation/)'s. นี่คือตัวอย่าง:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## หมายเหตุ

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // จะเกิดข้อยกเว้น IOException เนื่องจาก pres.pptx ถูกล็อกตลอดอายุการใช้งานของ Presentation
    // File::Delete(u"pres.pptx");
}
// หลังจากวัตถุ Presentation ถูกทำลาย ไฟล์จะถูกปลดล็อกและสามารถลบได้
IO::File::Delete(u"pres.pptx");
```

## ดูเพิ่มเติม

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Class [IBlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)