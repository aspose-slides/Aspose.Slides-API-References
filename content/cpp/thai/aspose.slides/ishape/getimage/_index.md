---
title: GetImage()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "คืนภาพย่อของรูปร่าง. ShapeThumbnailBounds::Shape shape thumbnail bounds type is used by default."
type: docs
weight: 547
url: /th/aspose.slides/ishape/getimage/
---
## IShape::GetImage() เมธอด


คืนภาพย่อของรูปร่าง [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) ประเภทขอบเขตภาพย่อของรูปร่างจะถูกใช้เป็นค่าเริ่มต้น

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```


### ค่าที่ส่งกลับ

[Shape](../../shape/) thumbnail.

## IShape::GetImage(ShapeThumbnailBounds, float, float) เมธอด


คืนภาพย่อของรูปร่าง

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) ประเภทขอบเขตภาพย่อ |
| scaleX | **float** | สเกล X |
| scaleY | **float** | สเกล Y |

### ค่าที่ส่งกลับ

[Shape](../../shape/) thumbnail หรือ null ในกรณีที่ [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) ถูกใช้และรูปร่างไม่มีองค์ประกอบที่มองเห็นได้

## See Also

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)