---
title: LoadingStreamBehavior
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "System::IO::Stream ที่ถูกส่งไปยังเมธอดจะถือเป็น Binary Large Object (BLOB) (ดูรายละเอียดใน IBlobManagementOptions). ค่าของ enumeration นี้ระบุว่าควรจัดการ System::IO::Stream อย่างไรเมื่อส่งไปยังเมธอด. ขึ้นอยู่กับความต้องการ การตัดสินใจต่าง ๆ สามารถทำได้เพื่อให้ได้พฤติกรรมที่มีประสิทธิภาพสูงสุด."
type: docs
weight: 6735
url: /th/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

[System::IO::Stream](../../system.io/stream/) ที่ส่งผ่านไปยังเมธอดจะถูกพิจารณาเป็น Binary Large Object (BLOB) (ดูรายละเอียดใน [IBlobManagementOptions](../iblobmanagementoptions/)). ค่าของ enumeration นี้ระบุว่า [System::IO::Stream](../../system.io/stream/) ควรได้รับการจัดการอย่างไรเมื่อถูกส่งผ่านไปยังเมธอด. ขึ้นอยู่กับความต้องการ การตัดสินใจที่แตกต่างกันอาจถูกทำเพื่อให้ได้พฤติกรรมที่มีประสิทธิภาพสูงสุด.

```cpp
enum class LoadingStreamBehavior
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | สตรีมจะถูกอ่านจนถึงจุดสิ้นสุดแล้วปล่อย - คือ จะรับประกันว่าสตรีมนี้จะไม่ถูกใช้โดยอ็อบเจ็กต์ [IPresentation](../ipresentation/) ในอนาคต. สามารถถูกปิดโดยโค้ดของไคลเอนต์หรือใช้ในทางอื่นได้. |
| KeepLocked | 1 | สตรีมจะถูกล็อกภายในอ็อบเจ็กต์ [IPresentation](../ipresentation/), คือ การเป็นเจ้าของสตรีมจะถูกโอนย้าย. อ็อบเจ็กต์ [IPresentation](../ipresentation/) จะรับผิดชอบในการกำจัดสตรีมอย่างถูกต้องเมื่ออ็อบเจ็กต์นี้ถูกกำจัดเอง. พฤติกรรมนี้มีประโยชน์อย่างยิ่งเมื่อคุณต้องการทำการ serialize ไฟล์ BLOB ขนาดใหญ่ (เช่น วิดีโอหรือออดิโอขนาดใหญ่ - ดูรายละเอียดใน [IBlobManagementOptions](../iblobmanagementoptions/)) และต้องการป้องกันการโหลดไฟล์นี้เข้าสู่หน่วยความจำหรือปัญหาประสิทธิภาพอื่น ๆ. คุณอาจเปิด [System::IO::FileStream](../../system.io/filestream/) สำหรับไฟล์นี้และส่งต่อไปยังเมธอด โดยเลือก [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior. |

## ดูเพิ่มเติม

* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)