---
title: GetImage()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ส่งคืนรูปย่อของรูปร่าง. ShapeThumbnailBounds::Shape ประเภทขอบเขตรูปย่อของรูปร่างใช้เป็นค่าเริ่มต้น."
type: docs
weight: 651
url: /th/aspose.slides/shape/getimage/
---
## Shape::GetImage() เมธอด

ส่งคืนรูปย่อของรูปร่าง [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) ประเภทของขอบเขตรูปย่อของรูปร่างใช้เป็นค่าเริ่มต้น

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```

### ค่าที่ส่งกลับ

[Shape](../) รูปย่อ

## Shape::GetImage(ShapeThumbnailBounds, float, float) เมธอด

ส่งคืนรูปย่อของรูปร่าง

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) ประเภทของขอบเขตรูปย่อ |
| scaleX | **float** | สเกล X |
| scaleY | **float** | สเกล Y |

### ค่าที่ส่งกลับ

[Shape](../) รูปย่อ หรือ null ในกรณีที่ [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) ถูกใช้และรูปร่างไม่มีองค์ประกอบที่มองเห็นได้

## ดูเพิ่มเติม

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IImage](../../iimage/)
* คลาส [Shape](../)
* เนมสเปส [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)