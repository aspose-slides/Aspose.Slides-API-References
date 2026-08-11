---
title: AddAudio()
second_title: Aspose.Slides برای مرجع API C++
description: یک نسخه از فایل صوتی را از ارائه‌ای دیگر اضافه می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) متد

یک نسخه از فایل صوتی را از ارائه‌ای دیگر اضافه می‌کند.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | صدای منبع. |

### مقدار بازگشتی

صدای اضافه شده.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) متد

یک صدا را از جریان ایجاد کرده و به ارائه اضافه می‌کند.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریانی که صدا از آن اضافه می‌شود. |

### مقدار بازگشتی

صدای اضافه شده.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) متد

یک صدا را از جریان ایجاد کرده و به ارائه اضافه می‌کند.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریانی که صدای ویدیو از آن اضافه می‌شود. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | رفتاری که بر روی جریان اعمال خواهد شد. |

### مقدار بازگشتی

صدای اضافه شده.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) متد

یک صدا را از آرایه بایت ایجاد کرده و به ارائه اضافه می‌کند.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) بایت. |

### مقدار بازگشتی

صدای اضافه شده.

## موارد مرتبط

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [AudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)