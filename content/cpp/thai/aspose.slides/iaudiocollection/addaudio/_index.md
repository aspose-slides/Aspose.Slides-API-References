---
title: AddAudio()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มสำเนาไฟล์เสียงจากงานนำเสนออื่น
type: docs
weight: 14
url: /th/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) เมธอด

เพิ่มสำเนาไฟล์เสียงจากงานนำเสนออื่น

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### พารามิเตอร์

| Parameter | Type | Description |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | ไฟล์เสียงต้นฉบับ |

### ค่าที่ส่งกลับ

ไฟล์เสียงที่เพิ่มแล้ว

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) เมธอด

สร้างและเพิ่มไฟล์เสียงเข้าสู่งานนำเสนอจากสตรีม

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### พารามิเตอร์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่ใช้เพิ่มไฟล์เสียง |

### ค่าที่ส่งกลับ

ไฟล์เสียงที่เพิ่มแล้ว

ล้าสมัย
:   ใช้ AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). เมธอดจะถูกลบในรุ่น 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) เมธอด

สร้างและเพิ่มไฟล์เสียงเข้าสู่งานนำเสนอจากสตรีม

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### พารามิเตอร์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่ใช้เพิ่มไฟล์เสียงวิดีโอ |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | พฤติกรรมที่จะใช้กับสตรีม |

### ค่าที่ส่งกลับ

ไฟล์เสียงที่เพิ่มแล้ว

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) เมธอด

สร้างและเพิ่มไฟล์เสียงเข้าสู่งานนำเสนอจากอาเรย์ไบต์

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### พารามิเตอร์

| Parameter | Type | Description |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) ไบต์ |

### ค่าที่ส่งกลับ

ไฟล์เสียงที่เพิ่มแล้ว

## ดูเพิ่มเติม

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IAudio](../../iaudio/)
* คลาส [IAudioCollection](../)
* คลาส [Stream](../../../system.io/stream/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)