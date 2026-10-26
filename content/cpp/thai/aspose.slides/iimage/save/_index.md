---
title: Save()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: บันทึกรูปภาพลงในไฟล์.
type: docs
weight: 40
url: /th/aspose.slides/iimage/save/
---
## IImage::Save(System::String) เมธอด


บันทึกรูปภาพลงในไฟล์.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | เส้นทางไปยังไฟล์ที่ภาพจะถูกบันทึก. |

## IImage::Save(System::String, ImageFormat) เมธอด


บันทึกรูปภาพลงในไฟล์ในรูปแบบที่ระบุ.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | เส้นทางไปยังไฟล์ที่ภาพจะถูกบันทึก. |
| format | [ImageFormat](../../imageformat/) | รูปแบบภาพ. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) เมธอด


บันทึกรูปภาพลงในสตรีมในรูปแบบที่ระบุ.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่ภาพจะถูกบันทึก. |
| format | [ImageFormat](../../imageformat/) | รูปแบบภาพ. |

## IImage::Save(System::String, ImageFormat, int32_t) เมธอด


บันทึกรูปภาพลงในไฟล์ในรูปแบบและคุณภาพที่ระบุ.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | เส้นทางไปยังไฟล์ที่ภาพจะถูกบันทึก. |
| format | [ImageFormat](../../imageformat/) | รูปแบบภาพ. |
| quality | **int32_t** | คุณภาพของภาพที่บันทึก (0 ถึง 100).  

 พารามิเตอร์นี้มีผลเฉพาะการบันทึกใน [ImageFormat::Jpeg](../../imageformat/); สำหรับรูปแบบอื่นทั้งหมดจะถูกละเว้น. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) เมธอด


บันทึกรูปภาพลงในสตรีมในรูปแบบและคุณภาพที่ระบุ.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่ภาพจะถูกบันทึก. |
| format | [ImageFormat](../../imageformat/) | รูปแบบภาพ. |
| quality | **int32_t** | คุณภาพของภาพที่บันทึก (0 ถึง 100).  

 พารามิเตอร์นี้มีผลเฉพาะการบันทึกใน [ImageFormat::Jpeg](../../imageformat/); สำหรับรูปแบบอื่นทั้งหมดจะถูกละเว้น. |

## ดูเพิ่มเติม

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IImage](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)