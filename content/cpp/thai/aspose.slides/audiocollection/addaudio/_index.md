---
title: AddAudio()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มสำเนาของไฟล์เสียงจากงานนำเสนออื่น
type: docs
weight: 53
url: /th/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) เมธอด

เพิ่มสำเนาของไฟล์เสียงจากงานนำเสนออื่น

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | แหล่งเสียง. |

### ค่าที่ส่งกลับ

เสียงที่เพิ่ม

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) เมธอด

สร้างและเพิ่มเสียงลงในงานนำเสนอจากสตรีม

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่เพิ่มเสียงจาก. |

### ค่าที่ส่งกลับ

เสียงที่เพิ่ม

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) เมธอด

สร้างและเพิ่มเสียงลงในงานนำเสนอจากสตรีม

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมที่เพิ่มเสียงวิดีโอจาก. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | พฤติกรรมที่จะใช้กับสตรีม. |

### ค่าที่ส่งกลับ

เสียงที่เพิ่ม

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) เมธอด

สร้างและเพิ่มเสียงลงในงานนำเสนอจากอาร์เรย์ไบต์

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) ไบต์. |

### ค่าที่ส่งกลับ

เสียงที่เพิ่ม

## ดูเพิ่มเติม

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [AudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)