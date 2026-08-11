---
title: AddVideoFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: یک فریم ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعه‌ اشکال اضافه می‌نماید.
type: docs
weight: 170
url: /fa/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) متد

یک فریم ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعه‌ اشکال اضافه می‌نماید.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم ویدئویی جدید، به نقاط. |
| y | **float** | مختصات y فریم ویدئویی جدید، به نقاط. |
| width | **float** | عرض فریم ویدئویی جدید، به نقاط. |
| height | **float** | ارتفاع فریم ویدئویی جدید، به نقاط. |
| fname | [System::String](../../../system/string/) | مسیر یا نام فایل ویدئویی برای جاسازی. |

### مقدار بازگشتی

[IVideoFrame](../../ivideoframe/) تازه ایجاد شده.

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) متد

یک فریم ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعه‌ اشکال اضافه می‌نماید.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم ویدئویی جدید، به نقاط. |
| y | **float** | مختصات y فریم ویدئویی جدید، به نقاط. |
| width | **float** | عرض فریم ویدئویی جدید، به نقاط. |
| height | **float** | ارتفاع فریم ویدئویی جدید، به نقاط. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | [IVideo](../../ivideo/) برای جاسازی در فریم ویدئویی. |

### مقدار بازگشتی

[IVideoFrame](../../ivideoframe/) تازه ایجاد شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IVideoFrame](../../ivideoframe/)
* کلاس [String](../../../system/string/)
* کلاس [IShapeCollection](../)
* کلاس [IVideo](../../ivideo/)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)