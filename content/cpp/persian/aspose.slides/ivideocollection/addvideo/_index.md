---
title: AddVideo()
second_title: مرجع API Aspose.Slides برای C++
description: یک کپی از فایل ویدئویی را از یک ارائه دیگر اضافه می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) متد

یک نسخه از فایل ویدئویی را از ارائه‌ای دیگر اضافه می‌کند.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | ویدئوی منبع. |

### مقدار بازگشتی

ویدئوی اضافه شده.

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) متد

یک ویدئو را از جریان ایجاد و به ارائه اضافه می‌کند.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریانی که فایل ویدئویی از آن اضافه می‌شود. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | رفتاری که بر روی جریان اعمال خواهد شد. |

### مقدار بازگشتی

[IVideo](../../ivideo/) اضافه شد.

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) متد

یک ویدئو را از آرایه بایت ایجاد و به ارائه اضافه می‌کند.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) بایت. |

### مقدار بازگشتی

ویدئوی اضافه شده.

## همچنین ببینید

* enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* typedef [SharedPtr](../../../system/sharedptr/)
* typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [IVideo](../../ivideo/)
* کلاس [IVideoCollection](../)
* کلاس [Stream](../../../system.io/stream/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)