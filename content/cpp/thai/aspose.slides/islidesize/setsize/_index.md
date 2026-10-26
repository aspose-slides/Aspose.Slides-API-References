---
title: SetSize()
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: "กำหนดขนาดสไลด์โดยประเภทและปรับสเกลเนื้อหาที่มีอยู่ การกำหนดค่าใด ๆ ที่ไม่ใช่ SlideSizeType::Custom จะปรับ ISlideSize::get_Size ตามประเภทที่เลือก ขณะเดียวกันคงไว้ ISlideSize::get_Orientation."
type: docs
weight: 53
url: /th/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) เมธอด

ตั้งค่าขนาดสไลด์โดยใช้ประเภทและปรับสเกลเนื้อหาที่มีอยู่ การกำหนดค่าใด ๆ ที่ไม่ใช่ [SlideSizeType::Custom](../../slidesizetype/) จะปรับ [ISlideSize::get_Size](../get_size/) ตามประเภทที่เลือก ในขณะเดียวกันคงไว้ [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | ขนาดสไลด์ที่กำหนดไว้ล่วงหน้าเพื่อใช้ |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | โหมดการปรับสเกลเนื้อหาที่จะใช้ |

## หมายเหตุ

การกำหนดค่าใด ๆ ที่ไม่ใช่ [SlideSizeType::Custom](../../slidesizetype/) จะปรับ [System::Drawing::Size](../../../system.drawing/size/) ตามประเภทที่เลือก ในขณะเดียวกันคงไว้ [Orientation](../../orientation/). 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) เมธอด

ตั้งค่าขนาดสไลด์โดยกำหนดค่าอย่างชัดเจนและปรับสเกลเนื้อหาที่มีอยู่ การรีเซ็ตค่า [ISlideSize::get_Type](../get_type/) เป็น [SlideSizeType::Custom](../../slidesizetype/) และตั้งค่า [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| width | **float** | ความกว้างสไลด์ใหม่เป็นหน่วยจุด |
| height | **float** | ความสูงสไลด์ใหม่เป็นหน่วยจุด |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | โหมดการปรับสเกลเนื้อหาที่จะใช้ |

## หมายเหตุ

การรีเซ็ตคุณสมบัติ [ISlideSize::get_Type](../get_type/) เป็น [SlideSizeType::Custom](../../slidesizetype/) และตั้งค่า [Orientation](../../orientation/). 

## ดูเพิ่มเติม

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* คลาส [ISlideSize](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)