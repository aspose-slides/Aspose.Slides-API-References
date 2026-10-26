---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส Presentation สามารถเป็นเจ้าของแหล่งที่มา - ไฟล์หรือสตรีม ระหว่างช่วงอายุของตัวอย่างได้หรือไม่ หากตัวอย่างเป็นเจ้าของ จะทำการล็อกแหล่งที่มา สิ่งนี้ช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งที่มา (สตรีมหรือไฟล์) ไม่สามารถเปลี่ยนแปลงได้ระหว่างช่วงอายุของตัวอย่าง Presentation นี้ ตัวอย่างเช่น:"
type: docs
weight: 14
url: /th/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) เมธอด

คุณสมบัตินี้กำหนดว่าตัวอย่างของคลาส [Presentation](../../presentation/) สามารถเป็นเจ้าของแหล่งที่มา - ไฟล์หรือสตรีม ระหว่างช่วงอายุของตัวอย่างได้หรือไม่ หากตัวอย่างเป็นเจ้าของจะทำการล็อกแหล่งที่มา สิ่งนี้ช่วยปรับปรุงการใช้หน่วยความจำและประสิทธิภาพขณะทำงานกับ BLOBs แต่แหล่งที่มา (สตรีมหรือไฟล์) ไม่สามารถเปลี่ยนแปลงได้ระหว่างช่วงอายุของตัวอย่าง [Presentation](../../presentation/)'s ตัวอย่างนี้ ตัวอย่างดังต่อไปนี้:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## หมายเหตุ



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException จะถูกโยนเพราะ pres.pptx ถูกล็อกตลอดอายุของ Presentation
    // File::Delete(u"pres.pptx");
}
// หลังจากอ็อบเจ็กต์ Presentation ถูกทำลาย ไฟล์จะถูกปลดล็อกและสามารถลบได้
IO::File::Delete(u"pres.pptx");
```

## ดูเพิ่มเติม

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Class [IBlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)