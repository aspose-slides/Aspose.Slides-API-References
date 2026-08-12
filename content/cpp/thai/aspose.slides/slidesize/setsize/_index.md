---
title: SetSize()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: กำหนดขนาดสไลด์โดยใช้ประเภทและปรับสเกลเนื้อหาเดิม.
type: docs
weight: 53
url: /th/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) เมธอด

กำหนดขนาดสไลด์ตามประเภทและปรับสเกลเนื้อหาเดิม

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | ขนาดสไลด์ที่กำหนดไว้ล่วงหน้าที่จะใช้ |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | โหมดการปรับสเกลเนื้อหาที่จะใช้ |
## หมายเหตุ

การกำหนดค่าที่ไม่ใช่ [SlideSizeType::Custom](../../slidesizetype/) จะปรับ [SlideSize::get_Size](../get_size/) ตามประเภทที่เลือก ในขณะที่คงไว้ซึ่ง [SlideSize::get_Orientation](../get_orientation/)  

## SlideSize::SetSize(float, float, SlideSizeScaleType) เมธอด

กำหนดมิติของสไลด์โดยตรงและปรับสเกลเนื้อหาเดิม

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| width | **float** | ความกว้างของสไลด์ใหม่ หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของสไลด์ใหม่ หน่วยเป็นพอยต์ |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | โหมดการปรับสเกลเนื้อหาที่จะใช้ |
## หมายเหตุ

การดำเนินการนี้จะรีเซ็ตพรอพเพอร์ตี้ [SlideSize::get_Type](../get_type/) เป็น [SlideSizeType::Custom](../../slidesizetype/) และตั้งค่า [Orientation](../../orientation/)  

## ดูเพิ่มเติม

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* คลาส [SlideSize](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)