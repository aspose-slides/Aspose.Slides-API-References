---
title: Contains()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าคอลเลกชัน ICollection มีค่าที่ระบุหรือไม่
type: docs
weight: 118
url: /th/aspose.slides.animation/behaviorpropertycollection/contains/
---
## BehaviorPropertyCollection::Contains(const System::SharedPtr\<IBehaviorProperty\>\&) const เมธอด

กำหนดว่า [ICollection](../../../system.collections.generic/icollection/) มีค่าที่ระบุหรือไม่

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | คุณสมบัติที่จะค้นหาใน [ICollection](../../../system.collections.generic/icollection/). |

### ค่าที่ส่งคืน

true หากพบ *item* ใน [ICollection](../../../system.collections.generic/icollection/); มิฉะนั้น false.

## BehaviorPropertyCollection::Contains(const System::String\&) const เมธอด

กำหนดว่า [ICollection](../../../system.collections.generic/icollection/) มีค่าที่ระบุหรือไม่

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::String &propertyValue) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | ค่าของคุณสมบัติที่จะค้นหาใน [ICollection](../../../system.collections.generic/icollection/). |

### ค่าที่ส่งคืน

true หากพบ *propertyValue* ใน [ICollection](../../../system.collections.generic/icollection/); มิฉะนั้น false.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IBehaviorProperty](../../ibehaviorproperty/)
* คลาส [BehaviorPropertyCollection](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)