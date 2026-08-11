---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: یک فریم Summary Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌نماید.
type: docs
weight: 157
url: /fa/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) متد

یک فریم Summary Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می نماید.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم Summary Zoom جدید، بر حسب نقطه. |
| y | **float** | مختصات y فریم Summary Zoom جدید، بر حسب نقطه. |
| width | **float** | عرض فریم Summary Zoom جدید، بر حسب نقطه. |
| height | **float** | ارتفاع فریم Summary Zoom جدید، بر حسب نقطه. |

### مقدار بازگشت

‏[ISummaryZoomFrame](../../isummaryzoomframe/) تازه ایجاد شده.

## توضیحات

این متد یک Summary Zoom جدید ایجاد می‌کند و مجموعه‌ای از اشیاء را برای تمام بخش‌های این ارائه در آن قرار می‌دهد.  

این مثال افزودن یک شیء Summary Zoom به انتهای یک مجموعه را نشان می‌دهد (فرض کنید حداقل دو بخش در ارائه "Presentation.pptx" وجود دارد): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## نگاه کنید به

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISummaryZoomFrame](../../isummaryzoomframe/)
* کلاس [ShapeCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)