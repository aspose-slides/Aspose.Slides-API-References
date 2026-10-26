---
title: InsertClone()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดในคอลเลกชัน.
type: docs
weight: 66
url: /th/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) เมธอด

แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดในคอลเลกชัน

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของสไลด์ใหม่ |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ที่ต้องทำสำเนา |

### ค่าที่ส่งคืน

สไลด์ที่แทรกแล้ว

## หมายเหตุ

เมื่อทำการโคลนสไลด์ระหว่างพรีเซนเทชันที่แตกต่างกัน มาสเตอร์ของสไลด์อาจถูกโคลนด้วย ระบบรีจิสทรีภายในจะใช้เพื่อติดตามมาสเตอร์ที่ถูกโคลนอัตโนมัติเพื่อป้องกันการสร้างสำเนาหลายครั้งของมาสเตอร์สไลด์เดียวกัน การโคลนมาสเตอร์สไลด์ด้วยตนเองจะไม่ได้รับการป้องกันหรือบันทึกไว้ หากต้องการควบคุมกระบวนการโคลนเพิ่มเติม ให้ใช้ [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) หรือ [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) สำหรับการโคลนสไลด์และ [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) สำหรับการโคลนมาสเตอร์

ตัวอย่างต่อไปนี้แสดงวิธีการโคลนในตำแหน่งอื่นภายใน [Presentation](../../presentation/). 
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation ที่แทนไฟล์พรีเซนเทชัน
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// คัดลอกสไลด์ที่ต้องการไปยังตำแหน่งสุดท้ายของคอลเลกชันสไลด์ในพรีเซนเทชันเดียวกัน
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// คัดลอกสไลด์ที่ต้องการไปยังดัชนีที่ระบุในพรีเซนเทชันเดียวกัน
slides->InsertClone(2, slides->idx_get(1));
// บันทึกพรีเซนเทชันที่แก้ไขแล้วลงดิสก์
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
ตัวอย่างต่อไปนี้แสดงวิธีการโคลนในตำแหน่งอื่นภายใน [Presentation](../../presentation/). 
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation เพื่อโหลดไฟล์พรีเซนเทชันต้นทาง
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// สร้างอินสแตนซ์ของคลาส Presentation สำหรับ PPTX ปลายทาง (ที่สไลด์จะถูกคัดลอก)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// บันทึกพรีเซนเทชันปลายทางลงดิสก์
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) เมธอด

แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดในคอลเลกชัน

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของสไลด์ใหม่ |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ที่ต้องทำสำเนา |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layout slide สำหรับสไลด์ใหม่ |

### ค่าที่ส่งคืน

สไลด์ที่แทรกแล้ว

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) เมธอด

แทรกสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งที่กำหนดในคอลเลกชัน จะเลือก Layout ที่เหมาะสมโดยอัตโนมัติจากมาสเตอร์ที่ระบุ (Layout ที่เหมาะสมคือ Layout ที่มี Type หรือ Name ตรงกับ Layout ของสไลด์ต้นฉบับ) หากไม่มี Layout ที่เหมาะสม Layout ของสไลด์ต้นฉบับจะถูกโคลน (ถ้า allowCloneMissingLayout เป็น true) หรือจะโยน PptxEditException (ถ้า allowCloneMissingLayout เป็น false)

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของสไลด์ใหม่ |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ที่ต้องทำสำเนา |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | มาสเตอร์สไลด์สำหรับสไลด์ใหม่ |
| allowCloneMissingLayout | **bool** | หากไม่มี Layout ที่เหมาะสมในมาสเตอร์ที่ระบุ Layout ของสไลด์ต้นฉบับจะถูกโคลน (ถ้า allowCloneMissingLayout เป็น true) หรือจะโยน PptxEditException (ถ้า allowCloneMissingLayout เป็น false) |

### ค่าที่ส่งคืน

สไลด์ที่แทรกแล้ว

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [ISlide](../../islide/)
* คลาส [SlideCollection](../)
* คลาส [ILayoutSlide](../../ilayoutslide/)
* คลาส [IMasterSlide](../../imasterslide/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)