---
title: AddVideo()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نسخه از فایل ویدئویی را از یک ارائه دیگر اضافه می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) متد


Adds a copy of an video file from an another presentation.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | ویدئوی منبع. |

### مقدار بازگشت

ویدیو اضافه شد.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) متد


Creates and adds a video to a presentation from stream.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریانی که ویدیو از آن اضافه می‌شود. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | رفتاری که بر روی جریان اعمال خواهد شد. |

### مقدار بازگشت

[IVideo](../../ivideo/) اضافه شد.

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) متد


Creates and adds a video to a presentation from byte array.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) بایت. |

### مقدار بازگشت

ویدیو اضافه شد.

## موارد مرتبط

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IVideo](../../ivideo/)
* Class [VideoCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)