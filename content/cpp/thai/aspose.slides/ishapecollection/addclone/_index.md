---
title: AddClone()
second_title: เอกสารอ้างอิง API Aspose.Slides สำหรับ C++
description: สร้างสำเนาของรูปร่างที่ระบุและเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง
type: docs
weight: 495
url: /th/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) เมธอด


สร้างสำเนาของรูปร่างที่ระบุและเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | รูปร่างที่ต้องการทำสำเนา |
| x | **float** | พิกัด x ของเฟรมรูปร่างที่ทำสำเนา, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรมรูปร่างที่ทำสำเนา, หน่วยเป็นจุด |
| width | **float** | ความกว้างของเฟรมรูปร่างที่ทำสำเนา, หน่วยเป็นจุด |
| height | **float** | ความสูงของเฟรมรูปร่างที่ทำสำเนา, หน่วยเป็นจุด |

### ค่าที่คืนกลับ

ออบเจ็กต์ที่สร้างใหม่ [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) เมธอด


สร้างสำเนาของรูปร่างที่ระบุและเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง. รูปร่างใหม่คงความกว้างและความสูงของ *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) ที่ต้องการทำสำเนา |
| x | **float** | พิกัด x ของเฟรมรูปร่างที่ทำสำเนา, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของเฟรมรูปร่างที่ทำสำเนา, หน่วยเป็นจุด |

### ค่าที่คืนกลับ

ออบเจ็กต์ที่สร้างใหม่ [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) เมธอด


สร้างสำเนาของรูปร่างที่ระบุและเพิ่มเข้าไปที่ส่วนท้ายของคอลเลกชันรูปร่าง. รูปร่างที่ทำสำเนารักษาตำแหน่งและขนาดของต้นฉบับ

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) ที่ต้องการทำสำเนา |

### ค่าที่คืนกลับ

ออบเจ็กต์ที่สร้างใหม่ [IShape](../../ishape/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IShape](../../ishape/)
* คลาส [IShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)