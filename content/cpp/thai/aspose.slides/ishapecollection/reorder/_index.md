---
title: Reorder()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ย้ายรูปร่างที่ระบุไปยังตำแหน่งใหม่ภายในคอลเลกชันของรูปร่าง.
type: docs
weight: 300
url: /th/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) เมธอด


ย้ายรูปร่างที่ระบุไปยังตำแหน่งใหม่ภในคอลเลกชันของรูปร่าง.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเป้าหมายที่เริ่มจากศูนย์ซึ่งรูปจะถูกวาง. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) ที่จะย้ายภในคอลเลกชัน. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) เมธอด


ย้ายรูปร่างที่ระบุภในคอลเลกชันของรูปร่าง โดยวางพวกมันเริ่มจากดัชนีที่กำหนด.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเป้าหมายที่เริ่มจากศูนย์ที่รูปร่างแรกที่ระบุจะถูกวาง; รูปร่างต่อไปจะวางตามลำดับที่ให้. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | หนึ่งหรือหลายอินสแตนซ์ของ [IShape](../../ishape/) ที่จะย้ายภในคอลเลกชัน. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IShape](../../ishape/)
* คลาส [IShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)