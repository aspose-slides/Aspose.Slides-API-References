---
title: GetImages()
second_title: อ้างอิง API ของ Aspose.Slides for C++
description: ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอ.
type: docs
weight: 417
url: /th/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) เมธอด


ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอ.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการแสดงผล. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) เมธอด


ส่งคืนอ็อบเจ็กต์ Thumbnail Bitmap สำหรับสไลด์ที่ระบุของงานนำเสนอ.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการแสดงผล. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | อาร์เรย์ที่บรรจุตำแหน่งสไลด์ เริ่มจาก 1. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) เมธอด


ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอโดยกำหนดการสเกลเอง.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการแสดงผล. |
| scaleX | **float** | ค่าที่ใช้สเกล Thumbnail ในทิศทางแกน x. |
| scaleY | **float** | ค่าที่ใช้สเกล Thumbnail ในทิศทางแกน y. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) เมธอด


ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอโดยกำหนดการสเกลเอง.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการแสดงผล. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | อาร์เรย์ที่บรรจุตำแหน่งสไลด์ เริ่มจาก 1. |
| scaleX | **float** | ค่าที่ใช้สเกล Thumbnail ในทิศทางแกน x. |
| scaleY | **float** | ค่าที่ใช้สเกล Thumbnail ในทิศทางแกน y. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) เมธอด


ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอโดยกำหนดขนาดที่ต้องการ.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการแสดงผล. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | ขนาดของภาพที่ต้องการสร้าง. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) เมธอด


ส่งคืนอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอโดยกำหนดขนาดที่ต้องการ.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการแสดงผล. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | อาร์เรย์ที่บรรจุตำแหน่งสไลด์ เริ่มจาก 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | ขนาดของภาพที่ต้องการสร้าง. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ Bitmap.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [IPresentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)