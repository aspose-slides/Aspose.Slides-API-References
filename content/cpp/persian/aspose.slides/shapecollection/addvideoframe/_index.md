---
title: AddVideoFrame()
second_title: Aspose.Slides برای مرجع API C++
description: یک فریم ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.
type: docs
weight: 209
url: /fa/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) متد

یک فریم ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم ویدئویی جدید، بر حسب نقطه. |
| y | **float** | مختصات y فریم ویدئویی جدید، بر حسب نقطه. |
| width | **float** | عرض فریم ویدئویی جدید، بر حسب نقطه. |
| height | **float** | ارتفاع فریم ویدئویی جدید، بر حسب نقطه. |
| fname | [System::String](../../../system/string/) | مسیر یا نام فایل ویدئویی برای جاسازی. |

### مقدار بازگشت

[IVideoFrame](../../ivideoframe/) تازه ایجاد شده.

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) متد

یک فریم ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم ویدئویی جدید، بر حسب نقطه. |
| y | **float** | مختصات y فریم ویدئویی جدید، بر حسب نقطه. |
| width | **float** | عرض فریم ویدئویی جدید، بر حسب نقطه. |
| height | **float** | ارتفاع فریم ویدئویی جدید، بر حسب نقطه. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | [IVideo](../../ivideo/) برای جاسازی در فریم ویدئویی. |

### مقدار بازگشت

[IVideoFrame](../../ivideoframe/) تازه ایجاد شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IVideoFrame](../../ivideoframe/)
* کلاس [String](../../../system/string/)
* کلاس [ShapeCollection](../)
* کلاس [IVideo](../../ivideo/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)