---
title: AddClone()
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่าง
type: docs
weight: 547
url: /th/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่าง

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | รูปร่างที่จะคัดลอก. |
| x | **float** | พิกัด x ของเฟรมของรูปร่างใหม่\\u2019s, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของเฟรมของรูปร่างใหม่\\u2019s, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของเฟรมของรูปร่างใหม่\\u2019s, หน่วยเป็นจุด. |
| height | **float** | ความสูงของเฟรมของรูปร่างใหม่\\u2019s, หน่วยเป็นจุด. |

### Return Value

The newly created [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method

สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่าง. รูปร่างใหม่จะคงความกว้างและความสูงของ *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | รูปร่างที่จะคัดลอก. |
| x | **float** | พิกัด x ของเฟรมของรูปร่างใหม่\\u2019s, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของเฟรมของรูปร่างใหม่\\u2019s, หน่วยเป็นจุด. |

### Return Value

The newly created [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

สร้างสำเนาของรูปร่างที่ระบุและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่าง. รูปร่างที่คัดลอกจะคงตำแหน่งและขนาดของรูปเดิม.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) ที่จะคัดลอก. |

### Return Value

The newly created [IShape](../../ishape/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IShape](../../ishape/)
* คลาส [ShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)