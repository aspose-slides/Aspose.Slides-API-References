---
title: InsertClone()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันของรูปร่างที่ดัชนีที่กำหนด
type: docs
weight: 560
url: /th/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) เมธอด

สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่กำหนด

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ที่ใช้ในการแทรกรูปร่างที่คัดลอก |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) ที่จะคัดลอก |
| x | **float** | พิกัด x ของกรอบรูปร่างที่คัดลอก\\u2019s, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของกรอบรูปร่างที่คัดลอก\\u2019s, หน่วยเป็นจุด |
| width | **float** | ความกว้างของกรอบรูปร่างที่คัดลอก\\u2019s, หน่วยเป็นจุด |
| height | **float** | ความสูงของกรอบรูปร่างที่คัดลอก\\u2019s, หน่วยเป็นจุด |

### ค่าที่ส่งกลับ

[IShape](../../ishape/) ที่สร้างขึ้นใหม่

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) เมธอด

สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่กำหนด รูปร่างใหม่คงความกว้างและความสูงของ *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ที่ใช้ในการแทรกรูปร่างที่คัดลอก |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) ที่จะคัดลอก |
| x | **float** | พิกัด x ของกรอบรูปร่างที่คัดลอก\\u2019s, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของกรอบรูปร่างที่คัดลอก\\u2019s, หน่วยเป็นจุด |

### ค่าที่ส่งกลับ

[IShape](../../ishape/) ที่สร้างขึ้นใหม่

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) เมธอด

สร้างสำเนาของรูปร่างที่ระบุและแทรกลงในคอลเลกชันของรูปร่างที่ตำแหน่งที่กำหนด รูปร่างที่คัดลอกคงตำแหน่งและขนาดของต้นฉบับ\\u2019s

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีที่เริ่มจากศูนย์ที่ใช้ในการแทรกรูปร่างที่คัดลอก |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) ที่จะคัดลอก |

### ค่าที่ส่งกลับ

[IShape](../../ishape/) ที่สร้างขึ้นใหม่

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IShape](../../ishape/)
* คลาส [ShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)