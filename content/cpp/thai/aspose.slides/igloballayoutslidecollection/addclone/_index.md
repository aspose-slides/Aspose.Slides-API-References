---
title: AddClone()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เพิ่มสำเนาของสไลด์เลย์เอาต์ที่ระบุลงในงานนำเสนอ.
type: docs
weight: 1
url: /th/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) เมธอด

เพิ่มสำเนาของสไลด์เลย์เอาต์ที่ระบุลงในงานนำเสนอ.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) เพื่อคัดลอก. |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม.

## หมายเหตุ



เมื่อคัดลอกเลย์เอาต์ระหว่างงานนำเสนอที่ต่างกัน มาสเตอร์ของเลย์เอาต์ก็อาจถูกคัดลอกด้วยเพื่อรักษาการจัดรูปแบบของต้นฉบับ มีการใช้เรจิสรีภายในเพื่อติดตามมาสเตอร์ที่ถูกคัดลอกโดยอัตโนมัติ เพื่อป้องกันการสร้างสำเนาซ้ำของมาสเตอร์สไลด์เดียวกัน การคัดลอกมาสเตอร์สไลด์ด้วยมือจะไม่ถูกป้องกันหรือบันทึกไว้. 

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) เมธอด


เพิ่มสำเนาของสไลด์เลย์เอาต์ที่ระบุลงในงานนำเสนอ.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) เพื่อคัดลอก. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | มาสเตอร์สไลด์สำหรับเลย์เอาต์ใหม่. |

### ค่าที่ส่งกลับ

สไลด์ที่เพิ่ม.

## หมายเหตุ



เลย์เอาต์ใหม่จะเชื่อมโยงกับมาสเตอร์ที่กำหนดในงานนำเสนอปลายทาง ดังนั้นนี่คือการทำงานที่คล้ายกับการคัดลอก/วางพร้อมตัวเลือก \"Use Destination Theme\" ใน PowerPoint. 

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ILayoutSlide](../../ilayoutslide/)
* คลาส [IGlobalLayoutSlideCollection](../)
* คลาส [IMasterSlide](../../imasterslide/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)