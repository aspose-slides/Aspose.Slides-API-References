---
title: AddImage()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มสำเนาของภาพจากการนำเสนออื่น
type: docs
weight: 53
url: /th/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) เมธอด

เพิ่มสำเนาของภาพจากการนำเสนออื่น.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | ภาพต้นทาง. |

### ค่าที่ส่งกลับ

ภาพที่เพิ่ม.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) เมธอด

เพิ่มภาพลงในการนำเสนอ.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | ภาพที่จะเพิ่ม. |

### ค่าที่ส่งกลับ

ภาพที่เพิ่ม.

## หมายเหตุ

เมธอดนี้จะแปลงไฟล์เมตาฟายล์ WMF/EMF เป็นภาพ PNG แบบแรสเตอร์ก่อนแทรกเข้าสู่การนำเสนอ.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) เมธอด

เพิ่มภาพลงในการนำเสนอจากสตรีม.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | สตรีมที่ใช้เพิ่มภาพ. |

### ค่าที่ส่งกลับ

ภาพที่เพิ่ม.

## หมายเหตุ

เมธอดนี้สามารถเพิ่มไฟล์เมตาฟายล์ WMF/EMF ไปยังการนำเสนอได้โดยไม่ต้องแปลงเป็นภาพ PNG แบบแรสเตอร์.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) เมธอด

เพิ่มภาพลงในการนำเสนอจากสตรีม.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่ใช้เพิ่มภาพ. |

### ค่าที่ส่งกลับ

ภาพที่เพิ่ม.

## หมายเหตุ

เมธอดนี้สามารถเพิ่มไฟล์เมตาฟายล์ WMF/EMF ไปยังการนำเสนอได้โดยไม่ต้องแปลงเป็นภาพ PNG แบบแรสเตอร์.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) เมธอด

สร้างและเพิ่มภาพลงในการนำเสนอจากสตรีม.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่ใช้เพิ่มไฟล์ภาพจาก. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | พฤติกรรมที่จะถูกนำไปใช้กับสตรีม. |

### ค่าที่ส่งกลับ

เพิ่ม [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) เมธอด

เพิ่มภาพลงในการนำเสนอจากบัฟเฟอร์ที่ระบุ.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์. |

### ค่าที่ส่งกลับ

ภาพที่เพิ่ม.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) เมธอด

เพิ่มภาพลงในการนำเสนอจากอ็อบเจกต์ Svg.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | อ็อบเจกต์ภาพ Svg [ISvgImage](../../isvgimage/) |

### ค่าที่ส่งกลับ

ภาพที่เพิ่ม.

## ดูเพิ่มเติม

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [ImageCollection](../)
* Class [IImage](../../iimage/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)