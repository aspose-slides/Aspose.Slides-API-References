---
title: InsertAudioFrameLinked()
second_title: مرجع API Aspose.Slides برای C++
description: یک قاب صوتی جدید که به یک فایل صوتی خارجی پیوند داده شده است ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند.
type: docs
weight: 235
url: /fa/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) روش

یک قاب صوتی جدید که به یک فایل صوتی خارجی پیوند داده شده است ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفرمبنا که در آن قاب صوتی وارد می‌شود. |
| x | **float** | مختصات x قاب صوتی جدید، بر حسب نقطه‌ها. |
| y | **float** | مختصات y قاب صوتی جدید، بر حسب نقطه‌ها. |
| width | **float** | عرض قاب صوتی جدید، بر حسب نقطه‌ها. |
| height | **float** | ارتفاع قاب صوتی جدید، بر حسب نقطه‌ها. |
| fname | [System::String](../../../system/string/) | مسیر یا نام فایل صوتی خارجی برای پیوند. |

### مقدار بازگشتی

[IAudioFrame](../../iaudioframe/) تازه ایجاد شده.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAudioFrame](../../iaudioframe/)
* کلاس [String](../../../system/string/)
* کلاس [IShapeCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)