---
title: AddGroupShape()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างกลุ่มรูปร่างเปล่าใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่าง กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปร่างใด ๆ ที่ถูกเพิ่มเข้าไป
type: docs
weight: 352
url: /th/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() เมธอด

สร้างกลุ่มรูปร่างเปล่าใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่าง. กรอบของกลุ่มจะปรับอัตโนมัติเพื่อให้พอดีกับรูปร่างใด ๆ ที่ถูกเพิ่มเข้าไป

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### ค่าที่ส่งกลับ

[IGroupShape](../../igroupshape/) ที่สร้างใหม่

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) เมธอด

สร้างกลุ่มรูปร่างใหม่, แปลงภาพ SVG ที่ระบุเป็นรูปร่างแยกส่วน, และเพิ่มกลุ่มที่ได้ลงในส่วนท้ายของคอลเลกชันรูปร่าง.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) ที่มีเนื้อหาเวกเตอร์เพื่อแปลงเป็นรูปร่าง. |
| x | **float** | พิกัด x ของกรอบกลุ่ม, หน่วยเป็นพ้อยต์. |
| y | **float** | พิกัด y ของกรอบกลุ่ม, หน่วยเป็นพ้อยต์. |
| width | **float** | ความกว้างของกรอบกลุ่ม, หน่วยเป็นพ้อยต์. |
| height | **float** | ความสูงของกรอบกลุ่ม, หน่วยเป็นพ้อยต์. |

### ค่าที่ส่งกลับ

[IGroupShape](../../igroupshape/) ที่สร้างใหม่

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IGroupShape](../../igroupshape/)
* คลาส [IShapeCollection](../)
* คลาส [ISvgImage](../../isvgimage/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)