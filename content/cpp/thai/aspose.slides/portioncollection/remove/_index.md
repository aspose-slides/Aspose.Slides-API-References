---
title: Remove()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ลบการเกิดขึ้นครั้งแรกของอ็อบเจ็กต์ที่ระบุจาก ICollection.
type: docs
weight: 131
url: /th/aspose.slides/portioncollection/remove/
---
## PortionCollection::Remove(System::SharedPtr\<IPortion\>) เมธอด

ลบการเกิดขึ้นครั้งแรกของอ็อบเจ็กต์ที่ระบุจาก [ICollection](../../../system.collections.generic/icollection/).

```cpp
bool Aspose::Slides::PortionCollection::Remove(System::SharedPtr<IPortion> item) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | อ็อบเจ็กต์ที่จะลบจาก [ICollection](../../../system.collections.generic/icollection/). |

### ค่าที่ส่งคืน

true หาก *item* ถูกลบสำเร็จจาก [ICollection](../../../system.collections.generic/icollection/); มิฉะนั้น false. เมธอดนี้ยังจะคืนค่า false หากไม่พบ *item* ใน [ICollection](../../../system.collections.generic/icollection/) ดั้งเดิม.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortion](../../iportion/)
* Class [PortionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)