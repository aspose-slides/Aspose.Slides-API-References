---
title: AddVideo()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: เพิ่มสำเนาไฟล์วิดีโอจากงานนำเสนออื่น
type: docs
weight: 14
url: /th/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) เมธอด

เพิ่มสำเนาไฟล์วิดีโอจากงานนำเสนออื่น

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | วิดีโอแหล่งที่มา |

### ค่าที่ส่งคืน

วิดีโอที่เพิ่ม

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) เมธอด

สร้างและเพิ่มวิดีโอลงในงานนำเสนอจากสตรีม

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่ใช้เพิ่มไฟล์วิดีโอ |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | พฤติกรรมที่จะนำไปใช้กับสตรีม |

### ค่าที่ส่งคืน

เพิ่ม [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) เมธอด

สร้างและเพิ่มวิดีโอลงในงานนำเสนอจากอาร์เรย์ไบต์

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) ไบต์ |

### ค่าที่ส่งคืน

วิดีโอที่เพิ่ม

## ดูเพิ่มเติม

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IVideo](../../ivideo/)
* Class [IVideoCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)