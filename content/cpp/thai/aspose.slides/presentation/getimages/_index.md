---
title: GetImages()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนอ็อบเจกต์ Image สำหรับสไลด์ทั้งหมดของงานนำเสนอ
type: docs
weight: 456
url: /th/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) เมธอด

คืนค่าอ็อบเจกต์ Image สำหรับสไลด์ทั้งหมดของงานนำเสนอ

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือก Tiff |

### ค่าที่คืน

อ็อบเจกต์ Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) เมธอด

คืนค่าอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอ

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือก Tiff |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | อาเรย์ที่มีตำแหน่งสไลด์ เริ่มจาก 1 |

### ค่าที่คืน

อ็อบเจกต์ Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) เมธอด

คืนค่าอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยการปรับสเกลแบบกำหนดเอง

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือก Tiff |
| scaleX | **float** | ค่าที่ใช้ปรับขนาด Thumbnail นี้ในทิศทางแกน x |
| scaleY | **float** | ค่าที่ใช้ปรับขนาด Thumbnail นี้ในทิศทางแกน y |

### ค่าที่คืน

อ็อบเจกต์ Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) เมธอด

คืนค่าอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยการปรับสเกลแบบกำหนดเอง

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือก Tiff |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | อาเรย์ที่มีตำแหน่งสไลด์ เริ่มจาก 1 |
| scaleX | **float** | ค่าที่ใช้ปรับขนาด Thumbnail นี้ในทิศทางแกน x |
| scaleY | **float** | ค่าที่ใช้ปรับขนาด Thumbnail นี้ในทิศทางแกน y |

### ค่าที่คืน

อ็อบเจกต์ Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) เมธอด

คืนค่าอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยขนาดที่ระบุ

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือก Tiff |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | ขนาดของภาพที่จะสร้าง |

### ค่าที่คืน

อ็อบเจกต์ Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) เมธอด

คืนค่าอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยขนาดที่ระบุ

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือก Tiff |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | อาเรย์ที่มีตำแหน่งสไลด์ เริ่มจาก 1 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | ขนาดของภาพที่จะสร้าง |

### ค่าที่คืน

อ็อบเจกต์ Image.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IImage](../../iimage/)
* คลาส [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* คลาส [Presentation](../)
* คลาส [Size](../../../system.drawing/size/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)