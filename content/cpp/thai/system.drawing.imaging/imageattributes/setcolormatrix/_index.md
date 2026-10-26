---
title: SetColorMatrix()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตั้งค่าตารางปรับสี.
type: docs
weight: 183
url: /th/system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) เมธอด

ตั้งค่าตารางปรับสี.

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newColorMatrix | const [SharedPtr](../../../system/sharedptr/)\<[ColorMatrix](../../colormatrix/)\>\& | ตารางปรับสีที่จะตั้งค่า |
| mode | [ColorMatrixFlag](../../colormatrixflag/) | ระบุประเภทของภาพและสีที่จะได้รับผลกระทบจากตารางปรับสี |
| type | [ColorAdjustType](../../coloradjusttype/) | ระบุประเภทของอ็อบเจ็กต์ที่ตั้งค่าตารางปรับสี |

## ดูเพิ่มเติม

* Enum [ColorMatrixFlag](../../colormatrixflag/)
* Enum [ColorAdjustType](../../coloradjusttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ColorMatrix](../../colormatrix/)
* Class [ImageAttributes](../)
* Namespace [System::Drawing::Imaging](../../)
* Library [Aspose.Slides](../../../)