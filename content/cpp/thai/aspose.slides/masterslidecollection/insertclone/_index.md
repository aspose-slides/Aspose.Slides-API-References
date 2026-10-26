---
title: InsertClone()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: แทรกสำเนาของสไลด์แม่ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน สไลด์เลเอาต์ที่เชื่อมโยงจะถูกคัดลอกด้วย
type: docs
weight: 105
url: /th/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) เมธอด

แทรกสำเนาของสไลด์แม่ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน สไลด์เลเอาต์ที่เชื่อมโยงจะถูกคัดลอกด้วย

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของสไลด์ใหม่ |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) เพื่อคัดลอก |

### ค่าที่ส่งกลับ

สไลด์แม่ที่แทรกแล้ว

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีคัดลอกสไลด์แม่ใน PowerPoint [Presentation](../../presentation/) อื่น
```cpp
// สร้างอ็อบเจกต์คลาส Presentation เพื่อโหลดไฟล์การนำเสนอต้นฉบับ
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// สร้างอ็อบเจกต์คลาส Presentation สำหรับการนำเสนอปลายทาง (ที่สไลด์จะถูกคัดลอก)
auto destPres = System::MakeObject<Presentation>();

// สร้างอ็อบเจกต์ ISlide จากคอลเลกชันสไลด์ในการนำเสนอต้นฉบับพร้อมกับ
// สไลด์แม่
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// รับสไลด์แม่ของการนำเสนอปลายทาง
auto masters = destPres->get_Masters();
// คัดลอกสไลด์แม่ที่ต้องการจากการนำเสนอต้นฉบับไปยังคอลเลกชันของสไลด์แม่ใน
// การนำเสนอปลายทาง
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// คอลเลกชันของสไลด์ในการนำเสนอปลายทาง
auto slides = destPres->get_Slides();
// คัดลอกสไลด์ต้นฉบับไปยังคอลเลกชันสไลด์ปลายทาง.
slides->AddClone(sourceSlide, iSlide, true);
// บันทึกการนำเสนอปลายทางลงดิสก์
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlide](../../imasterslide/)
* Class [MasterSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)