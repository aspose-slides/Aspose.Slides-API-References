---
title: InsertAudioFrameLinked()
second_title: مرجع API Aspose.Slides برای C++
description: یک فریم صوتی جدید که به یک فایل صوتی خارجی لینک شده است ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیسی که مشخص شده درج می‌کند.
type: docs
weight: 274
url: /fa/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) متد

یک فریم صوتی جدید که به یک فایل صوتی خارجی لینک شده است ایجاد می‌کند و آن را در ShapeCollection در اندیس مشخص شده درج می‌کند.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-مبنایی که فریم صوتی در آن درج می‌شود. |
| x | **float** | مختصات x فریم صوتی جدید، بر حسب نقاط. |
| y | **float** | مختصات y فریم صوتی جدید، بر حسب نقاط. |
| width | **float** | عرض فریم صوتی جدید، بر حسب نقاط. |
| height | **float** | ارتفاع فریم صوتی جدید، بر حسب نقاط. |
| fname | [System::String](../../../system/string/) | مسیر یا نام فایل صوتی خارجی که باید لینک شود. |

### مقدار بازگشت

[IAudioFrame](../../iaudioframe/) جدید ساخته‌شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)