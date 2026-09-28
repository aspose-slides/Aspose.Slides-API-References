---
title: GetImage()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนอ็อบเจ็กต์ภาพที่มีการปรับสเกลแบบกำหนดเอง.
type: docs
weight: 105
url: /th/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) เมธอด


คืนอ็อบเจ็กต์ภาพที่มีการปรับสเกลแบบกำหนดเอง.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| scaleX | **float** | ค่าที่ใช้ปรับสเกลรูปย่อนี้ในทิศทางแกน x. |
| scaleY | **float** | ค่าที่ใช้ปรับสเกลรูปย่อนี้ในทิศทางแกน y. |

### ค่าที่ส่งกลับ

Image อ็อบเจ็กต์ [IImage](../../iimage/)

## ISlide::GetImage() เมธอด


คืนอ็อบเจ็กต์รูปภาพย่อ (20% ของขนาดจริง).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### ค่าที่ส่งกลับ

Image อ็อบเจ็กต์ [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) เมธอด


คืนอ็อบเจ็กต์ภาพที่มีขนาดที่ระบุ.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | ขนาดของภาพที่จะสร้าง. |

### ค่าที่ส่งกลับ

Image อ็อบเจ็กต์ [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) เมธอด


คืนอ็อบเจ็กต์บิตแมป TIFF ย่อที่มีพารามิเตอร์ที่ระบุ.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | ตัวเลือก Tiff. |

### ค่าที่ส่งกลับ

Image อ็อบเจ็กต์ [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) เมธอด


คืนอ็อบเจ็กต์บิตแมปย่อ.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการเรนเดอร์. |

### ค่าที่ส่งกลับ

Image อ็อบเจ็กต์ [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) เมธอด


คืนอ็อบเจ็กต์บิตแมปย่อที่มีการปรับสเกลแบบกำหนดเอง.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการเรนเดอร์. |
| scaleX | **float** | ค่าที่ใช้ปรับสเกลรูปย่อนี้ในทิศทางแกน x. |
| scaleY | **float** | ค่าที่ใช้ปรับสเกลรูปย่อนี้ในทิศทางแกน y. |

### ค่าที่ส่งกลับ

Image อ็อบเจ็กต์ [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) เมธอด


คืนอ็อบเจ็กต์บิตแมปย่อที่มีขนาดที่ระบุ.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการเรนเดอร์. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | ขนาดของภาพที่จะสร้าง. |

### ค่าที่ส่งกลับ

Image อ็อบเจ็กต์ [IImage](../../iimage/)

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IImage](../../iimage/)
* คลาส [ISlide](../)
* คลาส [Size](../../../system.drawing/size/)
* คลาส [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* คลาส [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)