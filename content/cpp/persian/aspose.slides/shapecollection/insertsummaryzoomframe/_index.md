---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: یک فریم Summary Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده وارد می‌نماید.
type: docs
weight: 170
url: /fa/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) متد

یک فریم Summary Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص‌شده وارد می‌نماید.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-پایه‌ای که فریم Summary Zoom در آن قرار می‌گیرد. |
| x | **float** | مختصات x فریم Summary Zoom جدید، بر حسب پوینت. |
| y | **float** | مختصات y فریم Summary Zoom جدید، بر حسب پوینت. |
| width | **float** | عرض فریم Summary Zoom جدید، بر حسب پوینت. |
| height | **float** | ارتفاع فریم Summary Zoom جدید، بر حسب پوینت. |

### مقدار بازگشت

[ISummaryZoomFrame](../../isummaryzoomframe/) جدید ایجاد شده.

## توضیحات

این متد فریم Summary Zoom را ایجاد می‌کند که پیوندهای خلاصه‌سازی را برای تمام بخش‌های ارائه جمع‌آوری می‌کند.

این مثال ایجاد و درج یک شیء Summary Zoom را در ایندکس مشخص شدهٔ یک مجموعه نشان می‌دهد (فرض کنید در ارائهٔ "Presentation.pptx" حداقل دو بخش وجود دارد):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISummaryZoomFrame](../../isummaryzoomframe/)
* کلاس [ShapeCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)