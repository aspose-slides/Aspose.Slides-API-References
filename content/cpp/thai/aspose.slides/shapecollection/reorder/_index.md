---
title: Reorder()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: ย้ายรูปร่างที่ระบุไปยังตำแหน่งใหม่ภายในคอลเลกชันของรูปร่าง
type: docs
weight: 339
url: /th/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) เมธอด

Moves the specified shape to a new position within the shape collection.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเป้าหมายที่เริ่มต้นจากศูนย์ที่รูปร่างจะถูกวาง |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) เพื่อย้ายภายในคอลเล็กชัน |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) เมธอด

Moves the specified shapes within the shape collection, placing them starting at the given index.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเป้าหมายที่เริ่มต้นจากศูนย์ที่รูปร่างแรกที่ระบุจะถูกวาง; รูปร่างต่อมาจะตามลำดับที่ให้ไว้ |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | [IShape](../../ishape/) หนึ่งหรือหลายอินสแตนซ์เพื่อย้ายภายในคอลเล็กชัน |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)