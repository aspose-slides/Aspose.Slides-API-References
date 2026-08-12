---
title: AddVideo()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มสำเนาของไฟล์วิดีโอจากงานนำเสนออื่น
type: docs
weight: 53
url: /th/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) เมธอด


เพิ่มสำเนาของไฟล์วิดีโอจากงานนำเสนออื่น.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | วิดีโอต้นทาง |

### ค่าที่ส่งกลับ

เพิ่มวิดีโอ.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) เมธอด


สร้างและเพิ่มวิดีโอไปยังงานนำเสนอจากสตรีม.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมเพื่อเพิ่มไฟล์วิดีโอจาก |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | พฤติกรรมที่จะนำไปใช้กับสตรีม |

### ค่าที่ส่งกลับ

เพิ่ม [IVideo](../../ivideo/).

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) เมธอด


สร้างและเพิ่มวิดีโอไปยังงานนำเสนอจากอาร์เรย์ไบต์.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) ไบต์ |

### ค่าที่ส่งกลับ

เพิ่มวิดีโอ.

## ดูเพิ่มเติม

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IVideo](../../ivideo/)
* คลาส [VideoCollection](../)
* คลาส [Stream](../../../system.io/stream/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)