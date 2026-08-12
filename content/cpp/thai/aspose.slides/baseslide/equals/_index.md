---
title: Equals()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าตัวอย่างสองอินสแตนซ์ของ IBaseSlide มีค่าเท่ากันหรือไม่ ค่าที่ส่งกลับจะคำนวณบนพื้นฐานของโครงสร้างสไลด์และเนื้อหาคงที่ สไลด์สองสไลด์จะเท่ากันหากรูปทรง, สไตล์, ข้อความ, แอนิเมชันและการตั้งค่าอื่น ๆ ฯลฯ มีค่าเท่ากัน การเปรียบเทียบจะไม่คำนึงถึงค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าของวันที่ปัจจุบันใน Date Placeholder.
type: docs
weight: 170
url: /th/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) เมธอด


กำหนดว่าตัวอย่าง [IBaseSlide](../../ibaseslide/) ทั้งสองเท่ากันหรือไม่ ค่าที่คืนจะคำนวณตามโครงสร้างของสไลด์และเนื้อหาคงที่ สไลด์สองสไลด์เท่ากันหากรูปทรง, สไตล์, ข้อความ, แอนิเมชันและการตั้งค่าอื่น ๆ ฯลฯ เท่ากัน การเปรียบเทียบไม่คำนึงถึงค่าตัวระบุเฉพาะ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าที่เป็นวันที่ปัจจุบันใน Date [Placeholder](../../placeholder/).

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | [IBaseSlide](../../ibaseslide/) เพื่อเปรียบเทียบกับ [IBaseSlide](../../ibaseslide/) ปัจจุบัน |

### ค่าที่คืน

**true** หาก [IBaseSlide](../../ibaseslide/) ที่ระบุเท่ากับ [IBaseSlide](../../ibaseslide/) ปัจจุบัน; มิฉะนั้น, **false**.
## หมายเหตุ



ตัวอย่างต่อไปนี้แสดงวิธีเปรียบเทียบสไลด์สองสไลด์. 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IBaseSlide](../../ibaseslide/)
* คลาส [BaseSlide](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)