---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: یک فریم جدید Summary Zoom ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص‌شده وارد می‌نماید.
type: docs
weight: 157
url: /fa/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) method

Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | شاخص صفر مبنا که فریم Summary Zoom در آن وارد می‌شود. |
| x | **float** | مختصات x فریم Summary Zoom جدید، به نقاط. |
| y | **float** | مختصات y فریم Summary Zoom جدید، به نقاط. |
| width | **float** | عرض فریم Summary Zoom جدید، به نقاط. |
| height | **float** | ارتفاع فریم Summary Zoom جدید، به نقاط. |

### مقدار بازگشت

[ISummaryZoomFrame](../../isummaryzoomframe/) جدید ایجاد شده.

## توضیحات

این متد فریم Summary Zoom را ایجاد می‌کند که لینک‌های خلاصهٔ همهٔ بخش‌های ارائه را گردآوری می‌نماید.

این مثال نشان می‌دهد چطور یک شیء Summary Zoom را در ایندکس مشخص‌شدهٔ یک مجموعه ایجاد و وارد کنید (فرض کنید در ارائهٔ «Presentation.pptx» حداقل دو بخش وجود دارد):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## نگاه کنید به

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISummaryZoomFrame](../../isummaryzoomframe/)
* کلاس [IShapeCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)