---
title: Save()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: บันทึกรูปภาพที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันไปยังไฟล์ที่ระบุในรูปแบบ PNG.
type: docs
weight: 1
url: /th/system.drawing/image/save/
---
## Image::Save(const String\&) เมธอด


บันทึกรูปภาพที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันไปยังไฟล์ที่ระบุในรูปแบบ PNG.

```cpp
void System::Drawing::Image::Save(const String &filename)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ชื่อไฟล์ที่จะบันทึกรูปภาพไปยัง |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) เมธอด


บันทึกรูปภาพที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันไปยังไฟล์ที่ระบุในรูปแบบที่กำหนด.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ชื่อไฟล์ที่จะบันทึกรูปภาพไปยัง |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | รูปแบบที่จะบันทึกรูปภาพ |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) เมธอด


บันทึกรูปภาพที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันไปยังสตรีมที่ระบุในรูปแบบที่กำหนด.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่จะบันทึกรูปภาพไปยัง |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | รูปแบบที่จะบันทึกรูปภาพ |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) เมธอด


บันทึกรูปภาพที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันไปยังไฟล์ที่ระบุโดยใช้ตัวเข้ารหัสและพารามิเตอร์ของตัวเข้ารหัสที่กำหนด.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ชื่อไฟล์ที่จะบันทึกรูปภาพไปยัง |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | ตัวเข้ารหัสที่จะใช้ |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | พารามิเตอร์ของตัวเข้ารหัสที่จะใช้ |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) เมธอด


บันทึกรูปภาพที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันไปยังสตรีมที่ระบุโดยใช้ตัวเข้ารหัสและพารามิเตอร์ของตัวเข้ารหัสที่กำหนด.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่จะบันทึกรูปภาพไปยัง |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | ตัวเข้ารหัสที่จะใช้ |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | พารามิเตอร์ของตัวเข้ารหัสที่จะใช้ |

## ดูเพิ่มเติม

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* คลาส [String](../../../system/string/)
* คลาส [Image](../)
* คลาส [Stream](../../../system.io/stream/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)