---
title: Remove()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ลบการปรากฏครั้งแรกของอ็อบเจกต์ที่ระบุออกจาก ICollection.
type: docs
weight: 339
url: /th/aspose.slides.effects/imagetransformoperationcollection/remove/
---
## ImageTransformOperationCollection::Remove(const System::SharedPtr\<IImageTransformOperation\>\&) เมธอด


ลบการปรากฏครั้งแรกของอ็อบเจกต์ที่เฉพาะเจาะจงออกจาก [ICollection](../../../system.collections.generic/icollection/).

```cpp
bool Aspose::Slides::Effects::ImageTransformOperationCollection::Remove(const System::SharedPtr<IImageTransformOperation> &item) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\& | อ็อบเจกต์ที่จะลบออกจาก [ICollection](../../../system.collections.generic/icollection/). |

### ค่าที่ส่งกลับ

true หาก *item* ถูกลบออกจาก [ICollection](../../../system.collections.generic/icollection/) อย่างสำเร็จ; มิฉะนั้น false. เมธอดนี้ยังคืนค่า false หาก *item* ไม่พบใน [ICollection](../../../system.collections.generic/icollection/) ดั้งเดิม.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IImageTransformOperation](../../iimagetransformoperation/)
* คลาส [ImageTransformOperationCollection](../)
* เนมสเปซ [Aspose::Slides::Effects](../../)
* ไลบรารี [Aspose.Slides](../../../)