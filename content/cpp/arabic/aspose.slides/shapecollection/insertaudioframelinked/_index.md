---
title: InsertAudioFrameLinked()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بإنشاء إطار صوتي جديد مرتبط بملف صوت خارجي ويضيفه إلى مجموعة الأشكال في الفهرس المحدد.
type: docs
weight: 274
url: /ar/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) طريقة

يقوم بإنشاء إطار صوتي جديد مرتبط بملف صوت خارجي ويضيفه إلى مجموعة الأشكال في الفهرس المحدد.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري الذي يتم عنده إدراج إطار الصوت. |
| x | **float** | الإحداثي السيني لإطار الصوت الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الصوت الجديد، بالنقاط. |
| width | **float** | عرض إطار الصوت الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الصوت الجديد، بالنقاط. |
| fname | [System::String](../../../system/string/) | المسار أو اسم ملف الصوت الخارجي للربط. |

### Return Value

الكائن [IAudioFrame](../../iaudioframe/) الذي تم إنشاؤه حديثًا.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IAudioFrame](../../iaudioframe/)
* فئة [String](../../../system/string/)
* فئة [ShapeCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)