---
title: InsertClone()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งดัชนีที่ระบุ
type: docs
weight: 508
url: /th/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) เมธอด

สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งดัชนีที่ระบุ

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ที่ต้องการแทรกรูปร่างที่ทำสำเนา |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) ที่ต้องการทำสำเนา |
| x | **float** | พิกัด x ของกรอบรูปร่างที่ทำสำเนา, หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของกรอบรูปร่างที่ทำสำเนา, หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของกรอบรูปร่างที่ทำสำเนา, หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของกรอบรูปร่างที่ทำสำเนา, หน่วยเป็นพอยต์ |

### ค่าที่คืนกลับ

ค่าที่สร้างใหม่เป็น [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) เมธอด

สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งดัชนีที่ระบุ รูปร่างใหม่จะคงความกว้างและความสูงของ *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ที่ต้องการแทรกรูปร่างที่ทำสำเนา |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) ที่ต้องการทำสำเนา |
| x | **float** | พิกัด x ของกรอบรูปร่างที่ทำสำเนา, หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของกรอบรูปร่างที่ทำสำเนา, หน่วยเป็นพอยต์ |

### ค่าที่คืนกลับ

ค่าที่สร้างใหม่เป็น [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) เมธอด

สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งดัชนีที่ระบุ รูปร่างที่ทำสำเนาจะคงตำแหน่งและขนาดของเดิม\\u2019

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ที่ต้องการแทรกรูปร่างที่ทำสำเนา |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) ที่ต้องการทำสำเนา |

### ค่าที่คืนกลับ

ค่าที่สร้างใหม่เป็น [IShape](../../ishape/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IShape](../../ishape/)
* คลาส [IShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)