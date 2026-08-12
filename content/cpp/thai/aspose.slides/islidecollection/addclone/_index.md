---
title: AddClone()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของคอลเลกชัน.
type: docs
weight: 14
url: /th/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) เมธอด


เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของคอลเลกชัน.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) เพื่อทำสำเนา |

### ค่าที่คืน

สไลด์ใหม่.

## หมายเหตุ



เมื่อทำการคัดลอกสไลด์ระหว่างการนำเสนอที่ต่างกันมาสไลด์มาสเตอร์ก็สามารถคัดลอกได้ด้วย. รีจิสทรีภายในถูกใช้เพื่อจัดการมาสเตอร์ที่ถูกคัดลอกโดยอัตโนมัติเพื่อป้องกันการสร้างสำเนาซ้ำของมาสเตอร์สไลด์เดียวกัน. การคัดลอกมาสเตอร์สไลด์ด้วยตนเองจะไม่ได้ถูกป้องกันหรือบันทึกไว้. หากคุณต้องการควบคุมกระบวนการคัดลอกเพิ่มเติมให้ใช้ [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) หรือ [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) สำหรับคัดลอกสไลด์, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) หรือ [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) สำหรับคัดลอกเลเอาต์ และ [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) สำหรับคัดลอกมาสเตอร์. 
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) เมธอด


เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของเซกชันที่ระบุ.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) เพื่อทำสำเนา |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) สำหรับสไลด์ใหม่ |

### ค่าที่คืน

สไลด์ใหม่.

## หมายเหตุ



```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// ตอนนี้ส่วนที่สองมีสำเนาของสไลด์แรก.
```


## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) เมธอด


เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของคอลเลกชัน.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) เพื่อทำสำเนา |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | เลเอาต์สไลด์สำหรับสไลด์ใหม่ |

### ค่าที่คืน

สไลด์ใหม่.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) เมธอด


เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุไปยังส่วนท้ายของคอลเลกชัน เลเอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจากมาสเตอร์ที่ระบุ (เลเอาต์ที่เหมาะสมคือเลเอาต์ที่มี Type หรือ Name เหมือนกับเลเอาต์ของสไลด์ต้นฉบับ) หากไม่มีเลเอาต์ที่เหมาะสม เลเอาต์ของสไลด์ต้นฉบับจะถูกคัดลอก (หาก allowCloneMissingLayout เป็น true) หรือจะเกิดข้อยกเว้น PptxEditException (หาก allowCloneMissingLayout เป็น false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) เพื่อทำสำเนา |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | มาสเตอร์สไลด์สำหรับสไลด์ใหม่ |
| allowCloneMissingLayout | **bool** | หากไม่มีเลเอาต์ที่เหมาะสมในมาสเตอร์ที่ระบุ เลเอาต์ของสไลด์ต้นฉบับจะถูกคัดลอก (ถ้า allowCloneMissingLayout เป็น true) หรือจะเกิดข้อยกเว้น PptxEditException (ถ้า allowCloneMissingLayout เป็น false). |

### ค่าที่คืน

สไลด์ใหม่.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlide](../../islide/)
* คลาส [ISlideCollection](../)
* คลาส [ISection](../../isection/)
* คลาส [ILayoutSlide](../../ilayoutslide/)
* คลาส [IMasterSlide](../../imasterslide/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)