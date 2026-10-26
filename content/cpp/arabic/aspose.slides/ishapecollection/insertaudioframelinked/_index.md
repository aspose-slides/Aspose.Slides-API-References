---
title: InsertAudioFrameLinked()
second_title: مرجع API Aspose.Slides للـ C++
description: يُنشئ إطار صوت جديد مرتبط بملف صوت خارجي ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.
type: docs
weight: 235
url: /ar/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) طريقة

إنشاء إطار صوتي جديد مرتبط بملف صوت خارجي وإدراجه في مجموعة الأشكال عند الفهرس المحدد.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يتم عنده إدراج إطار الصوت. |
| x | **float** | الإحداثي السيني لإطار الصوت الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي الصادي لإطار الصوت الجديد، بوحدات النقاط. |
| width | **float** | عرض إطار الصوت الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بوحدات النقاط. |
| fname | [System::String](../../../system/string/) | المسار أو اسم ملف الصوت الخارجي للربط. |

### قيمة الإرجاع

الـ[IAudioFrame](../../iaudioframe/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IAudioFrame](../../iaudioframe/)
* فئة [String](../../../system/string/)
* فئة [IShapeCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)