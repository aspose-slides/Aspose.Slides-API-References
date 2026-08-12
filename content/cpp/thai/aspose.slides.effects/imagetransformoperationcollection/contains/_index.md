---
title: Contains()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าคอลเลกชัน ICollection มีค่าที่เฉพาะหรือไม่
type: docs
weight: 313
url: /th/aspose.slides.effects/imagetransformoperationcollection/contains/
---
## ImageTransformOperationCollection::Contains(const System::SharedPtr\<IImageTransformOperation\>\&) const เมธอด

ระบุว่า [ICollection](../../../system.collections.generic/icollection/) มีค่าที่เฉพาะหรือไม่

```cpp
bool Aspose::Slides::Effects::ImageTransformOperationCollection::Contains(const System::SharedPtr<IImageTransformOperation> &item) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\& | วัตถุที่จะค้นหาใน [ICollection](../../../system.collections.generic/icollection/). |

### ค่าที่ส่งกลับ

true หาก *item* พบใน [ICollection](../../../system.collections.generic/icollection/); มิฉะนั้น false.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImageTransformOperation](../../iimagetransformoperation/)
* Class [ImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)