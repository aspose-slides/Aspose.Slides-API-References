---
title: AddVideoFrame()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ إطار فيديو جديدًا ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 170
url: /ar/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) طريقة

ينشئ إطار فيديو جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي X لإطار الفيديو الجديد، بالنقاط. |
| y | **float** | الإحداثي Y لإطار الفيديو الجديد، بالنقاط. |
| width | **float** | عرض إطار الفيديو الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الفيديو الجديد، بالنقاط. |
| fname | [System::String](../../../system/string/) | المسار أو اسم ملف الفيديو لتضمينه. |

### قيمة الإرجاع

الكائن [IVideoFrame](../../ivideoframe/) الذي تم إنشاؤه حديثًا.

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) طريقة

ينشئ إطار فيديو جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي X لإطار الفيديو الجديد، بالنقاط. |
| y | **float** | الإحداثي Y لإطار الفيديو الجديد، بالنقاط. |
| width | **float** | عرض إطار الفيديو الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار الفيديو الجديد، بالنقاط. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | الـ[IVideo](../../ivideo/) لتضمينه في إطار الفيديو. |

### قيمة الإرجاع

الكائن [IVideoFrame](../../ivideoframe/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoFrame](../../ivideoframe/)
* Class [String](../../../system/string/)
* Class [IShapeCollection](../)
* Class [IVideo](../../ivideo/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)