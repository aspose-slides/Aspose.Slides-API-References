---
title: GetImage()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: คืนอ็อบเจ็กต์รูปภาพพร้อมการสเกลที่กำหนดเอง.
type: docs
weight: 105
url: /th/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) เมธอด


คืนอ็อบเจ็กต์รูปภาพพร้อมการสเกลที่กำหนดเอง.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| scaleX | **float** | ค่าที่ใช้ในการสเกล Thumbnail นี้ในแนวแกน x. |
| scaleY | **float** | ค่าที่ใช้ในการสเกล Thumbnail นี้ในแนวแกน y. |

### ค่าที่ส่งกลับ

Image object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() เมธอด


คืนอ็อบเจ็กต์รูปภาพ Thumbnail (ขนาด 20% ของขนาดจริง).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### ค่าที่ส่งกลับ

Image object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) เมธอด


คืนอ็อบเจ็กต์รูปภาพที่มีขนาดตามที่ระบุ.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | ขนาดของรูปภาพที่จะสร้าง. |

### ค่าที่ส่งกลับ

Bitmap object.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) เมธอด


คืนอ็อบเจ็กต์บิตแม็พ TIFF Thumbnail พร้อมพารามิเตอร์ที่ระบุ.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | ตัวเลือก Tiff. |

### ค่าที่ส่งกลับ

Image object.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) เมธอด


คืนอ็อบเจ็กต์บิตแม็พ Thumbnail.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการเรนเดอร์. |

### ค่าที่ส่งกลับ

Bitmap objects.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) เมธอด


คืนอ็อบเจ็กต์บิตแม็พ Thumbnail พร้อมการสเกลที่กำหนดเอง.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการเรนเดอร์. |
| scaleX | **float** | ค่าที่ใช้ในการสเกล Thumbnail นี้ในแนวแกน x. |
| scaleY | **float** | ค่าที่ใช้ในการสเกล Thumbnail นี้ในแนวแกน y. |

### ค่าที่ส่งกลับ

Bitmap objects.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) เมธอด


คืนอ็อบเจ็กต์บิตแม็พ Thumbnail ที่มีขนาดตามที่ระบุ.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | ตัวเลือกการเรนเดอร์. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | ขนาดของรูปภาพที่จะสร้าง. |

### ค่าที่ส่งกลับ

Bitmap objects.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IImage](../../iimage/)
* คลาส [ISlide](../)
* คลาส [Size](../../../system.drawing/size/)
* คลาส [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* คลาส [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)