---
title: Remove()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ลบการปรากฏตัวแรกของอ็อบเจ็กต์เฉพาะจาก ICollection.
type: docs
weight: 131
url: /th/aspose.slides/paragraphcollection/remove/
---
## ParagraphCollection::Remove(System::SharedPtr\<IParagraph\>) เมธอด

ลบการปรากฏตัวแรกของอ็อบเจ็กต์เฉพาะจาก [ICollection](../../../system.collections.generic/icollection/).

```cpp
bool Aspose::Slides::ParagraphCollection::Remove(System::SharedPtr<IParagraph> item) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | อ็อบเจ็กต์ที่จะลบจาก [ICollection](../../../system.collections.generic/icollection/). |

### Return Value

true หาก *item* ถูกลบสำเร็จจาก [ICollection](../../../system.collections.generic/icollection/); หากไม่เช่นนั้น false. เมธอดนี้ยังคืนค่า false หากไม่พบ *item* ใน [ICollection](../../../system.collections.generic/icollection/) ดั้งเดิม.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IParagraph](../../iparagraph/)
* คลาส [ParagraphCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)