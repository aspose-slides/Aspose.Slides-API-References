---
title: Bitmap()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอ็อบเจ็กต์ Bitmap ใหม่จากภาพที่มีอยู่ตามที่ระบุ
type: docs
weight: 1
url: /th/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) คอนสตรักเตอร์

สร้างออบเจ็กต์ [Bitmap](../) ใหม่จากภาพที่มีอยู่ที่ระบุ

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่มีอยู่เพื่อสร้างภาพบิตแมปจาก |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) คอนสตรักเตอร์

สร้างออบเจ็กต์ [Bitmap](../) ใหม่จากสตรีมที่ระบุ

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่มีข้อมูลภาพ |
| useIcm | **bool** | ละเว้น |

## Bitmap::Bitmap(const String\&) คอนสตรักเตอร์

สร้างออบเจ็กต์ [Bitmap](../) ใหม่จากไฟล์ที่ระบุ

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ชื่อไฟล์ที่มีข้อมูลภาพ |

## Bitmap::Bitmap(const String\&, bool) คอนสตรักเตอร์

สร้างออบเจ็กต์ [Bitmap](../) ใหม่จากไฟล์ที่ระบุ

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ชื่อไฟล์ที่มีข้อมูลภาพ |
| useIcm | **bool** | ละเว้น |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) คอนสตรักเตอร์

สร้างออบเจ็กต์ [Bitmap](../) ใหม่ที่เป็นภาพบิตแมปที่มีความกว้าง, ความสูง, รูปแบบพิกเซลและข้อมูลพิกเซลตามที่ระบุ

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| width | int | ความกว้างของภาพ |
| height | int | ความสูงของภาพ |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | รูปแบบพิกเซลของภาพ |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) คอนสตรักเตอร์

สร้างออบเจ็กต์ [Bitmap](../) ใหม่จากภาพที่มีอยู่ที่ระบุ โดยปรับขนาดให้ตรงกับขนาดที่ระบุ

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่มีอยู่เพื่อสร้างภาพบิตแมปจาก |
| size | const [Size](../../size/)\& | ขนาดของภาพใหม่ |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) คอนสตรักเตอร์

สร้างออบเจ็กต์ [Bitmap](../) ใหม่จากภาพที่มีอยู่ที่ระบุ โดยปรับความกว้างและความสูงให้เป็นค่าที่ระบุ

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่มีอยู่เพื่อสร้างภาพบิตแมปจาก |
| width | int | ความกว้างของภาพใหม่ |
| height | int | ความสูงของภาพใหม่ |

## ดูเพิ่มเติม

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)