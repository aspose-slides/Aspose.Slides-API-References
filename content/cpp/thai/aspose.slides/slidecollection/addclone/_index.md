---
title: AddClone()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของคอลเลกชัน.
type: docs
weight: 53
url: /th/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) method

เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของคอลเลกชัน.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) เพื่อคัดลอก. |

### ค่าที่คืน

สไลด์ใหม่.

## หมายเหตุ

เมื่อทำการคัดลอกสไลด์ระหว่างการนำเสนอที่แตกต่างกัน มาสเตอร์ของสไลด์อาจถูกคัดลอกด้วย ระบบทะเบียนภายในจะถูกใช้เพื่อติดตามมาสเตอร์ที่ถูกคัดลอกโดยอัตโนมัติเพื่อป้องกันการสร้างสำเนาซ้ำของมาสเตอร์สไลด์เดียวกัน การคัดลอกมาสเตอร์สไลด์ด้วยตนเองจะไม่ได้ถูกป้องกันหรือบันทึก หากคุณต้องการควบคุมกระบวนการคัดลอกมากขึ้น ให้ใช้ [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) หรือ [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) สำหรับการคัดลอกสไลด์, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) หรือ [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) สำหรับการคัดลอกเลย์เอาต์และ [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) สำหรับการคัดลอกมาสเตอร์.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) method

เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของส่วนที่ระบุ.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) เพื่อคัดลอก. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) สำหรับสไลด์ใหม่. |

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

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method

เพิ่มสำเนาของสไลด์ที่ระบุไปยังส่วนท้ายของคอลเลกชัน.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) เพื่อคัดลอก. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | เลย์เอาต์สไลด์สำหรับสไลด์ใหม่. |

### ค่าที่คืน

สไลด์ใหม่.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method

เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุไปยังส่วนท้ายของคอลเลกชัน เลย์เอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจากมาสเตอร์ที่ระบุ (เลย์เอาต์ที่เหมาะสมคือเลย์เอาต์ที่มี Type หรือ Name เดียวกับเลย์เอาต์ของสไลด์ต้นฉบับ) หากไม่มีเลย์เอาต์ที่เหมาะสมแล้ว เลย์เอาต์ของสไลด์ต้นฉบับจะถูกคัดลอก (หาก allowCloneMissingLayout เป็น true) หรือจะเกิดข้อยกเว้น PptxEditException (หาก allowCloneMissingLayout เป็น false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) เพื่อคัดลอก. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | มาสเตอร์สไลด์สำหรับสไลด์ใหม่. |
| allowCloneMissingLayout | **bool** | หากไม่มีเลย์เอาต์ที่เหมาะสมในมาสเตอร์ที่ระบุแล้ว เลย์เอาต์ของสไลด์ต้นฉบับจะถูกคัดลอก (หาก allowCloneMissingLayout เป็น true) หรือจะเกิดข้อยกเว้น PptxEditException (หาก allowCloneMissingLayout เป็น false). |

### ค่าที่คืน

สไลด์ใหม่.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlide](../../islide/)
* คลาส [SlideCollection](../)
* คลาส [ISection](../../isection/)
* คลาส [ILayoutSlide](../../ilayoutslide/)
* คลาส [IMasterSlide](../../imasterslide/)
* เนมสเปส [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)