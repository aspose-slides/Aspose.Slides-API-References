---
title: AddAudio()
second_title: Aspose.Slides برای C++ مرجع API
description: یک کپی از فایل صوتی را از یک ارائه دیگر اضافه می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) method

یک کپی از فایل صوتی را از یک ارائه دیگر اضافه می‌کند.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | صوت منبع. |

### مقدار بازگشت

صوت اضافه‌شده.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) method

یک صدا از جریان ایجاد می‌کند و به ارائه اضافه می‌کند.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریانی که صدا از آن اضافه می‌شود. |

### مقدار بازگشت

صوت اضافه‌شده.

Deprecated
:   از AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior) استفاده کنید. این متد در نسخه 17.10 حذف خواهد شد.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method

یک صدا از جریان ایجاد می‌کند و به ارائه اضافه می‌کند.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریانی که صدا از آن اضافه می‌شود. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | رفتاری که بر روی جریان اعمال می‌شود. |

### مقدار بازگشت

صوت اضافه‌شده.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) method

یک صدا از آرایه بایت ایجاد می‌کند و به ارائه اضافه می‌کند.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) بایت. |

### مقدار بازگشت

صوت اضافه‌شده.

## ملاحظات

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [IAudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)