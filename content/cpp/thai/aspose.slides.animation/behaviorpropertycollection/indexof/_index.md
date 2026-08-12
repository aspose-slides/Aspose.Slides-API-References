---
title: IndexOf()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดดัชนีของรายการที่ระบุใน IList.
type: docs
weight: 40
url: /th/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const เมธอด

กำหนดดัชนีของรายการที่ระบุใน [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | วัตถุที่ต้องการค้นหาใน [IList](../../../system.collections.generic/ilist/). |

### ค่าที่ส่งกลับ

ดัชนีของ *item* หากพบในรายการ; มิฉะนั้น, -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const เมธอด

กำหนดดัชนีของรายการที่ระบุโดยค่าคุณสมบัติใน [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | ค่าของคุณสมบัติ |

### ค่าที่ส่งกลับ

ดัชนีของคุณสมบัติที่มีค่าตามที่ระบุ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IBehaviorProperty](../../ibehaviorproperty/)
* คลาส [BehaviorPropertyCollection](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)