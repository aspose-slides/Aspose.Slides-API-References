---
title: AddVideoFrame()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 209
url: /ar/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) طريقة

ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي السيني لإطار الفيديو الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي الصادي لإطار الفيديو الجديد، بوحدات النقاط. |
| width | **float** | عرض إطار الفيديو الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع إطار الفيديو الجديد، بوحدات النقاط. |
| fname | [System::String](../../../system/string/) | المسار أو اسم ملف الفيديو المراد تضمينه. |

### قيمة الإرجاع

ال[IVideoFrame](../../ivideoframe/) الذي تم إنشاؤه حديثًا.

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) طريقة

ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | الإحداثي السيني لإطار الفيديو الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي الصادي لإطار الفيديو الجديد، بوحدات النقاط. |
| width | **float** | عرض إطار الفيديو الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع إطار الفيديو الجديد، بوحدات النقاط. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | ال[IVideo](../../ivideo/) لتضمينه في إطار الفيديو. |

### قيمة الإرجاع

ال[IVideoFrame](../../ivideoframe/) الذي تم إنشاؤه حديثًا.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IVideoFrame](../../ivideoframe/)
* فئة [String](../../../system/string/)
* فئة [ShapeCollection](../)
* فئة [IVideo](../../ivideo/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)