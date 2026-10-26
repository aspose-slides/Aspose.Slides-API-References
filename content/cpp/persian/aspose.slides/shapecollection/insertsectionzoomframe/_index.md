---
title: InsertSectionZoomFrame()
second_title: مرجع API Aspose.Slides برای C++
description: یک فریم Zoom بخش جدید ایجاد می‌کند و آن را در مجموعه شکل‌ها در شاخص مشخص شده وارد می‌نماید.
type: docs
weight: 144
url: /fa/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) method

یک فریم Zoom جدید [Section](../../section/) ایجاد می‌کند و آن را در مجموعه شکل‌ها در شاخص مشخص شده وارد می‌کند.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | شاخص صفر پایه‌ای که فریم Zoom [Section](../../section/) در آن وارد شود. |
| x | **float** | مختصات x فریم Zoom جدید [Section](../../section/)، به نقطه. |
| y | **float** | مختصات y فریم Zoom جدید [Section](../../section/)، به نقطه. |
| width | **float** | عرض فریم Zoom جدید [Section](../../section/)، به نقطه. |
| height | **float** | ارتفاع فریم Zoom جدید [Section](../../section/)، به نقطه. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) ای که توسط فریم Zoom [Section](../../section/) ارجاع شده؛ باید به این ارائه تعلق داشته باشد و حداقل یک اسلاید داشته باشد. |

### مقدار بازگشت

[ISectionZoomFrame](../../isectionzoomframe/) جدید ایجاد شده.

## توضیحات

این مثال ایجاد و وارد کردن یک شیء Zoom [Section](../../section/) را در شاخص مشخص شده یک مجموعه نشان می‌دهد (فرض کنید که در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method

یک فریم Zoom جدید [Section](../../section/) با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در مجموعه شکل‌ها در شاخص مشخص شده وارد می‌کند.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | شاخص صفر پایه‌ای که فریم Zoom [Section](../../section/) در آن وارد شود. |
| x | **float** | مختصات x فریم Zoom جدید [Section](../../section/)، به نقطه. |
| y | **float** | مختصات y فریم Zoom جدید [Section](../../section/)، به نقطه. |
| width | **float** | عرض فریم Zoom جدید [Section](../../section/)، به نقطه. |
| height | **float** | ارتفاع فریم Zoom جدید [Section](../../section/)، به نقطه. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) ای که توسط فریم Zoom [Section](../../section/) ارجاع شده؛ باید به این ارائه تعلق داشته باشد و حداقل یک اسلاید داشته باشد. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | تصویری که در فریم Zoom [Section](../../section/) نمایش داده می‌شود. |

### مقدار بازگشت

[ISectionZoomFrame](../../isectionzoomframe/) جدید ایجاد شده.

## توضیحات

این مثال ایجاد و وارد کردن یک شیء Zoom [Section](../../section/) را در شاخص مشخص شده یک مجموعه نشان می‌دهد (فرض کنید که در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISectionZoomFrame](../../isectionzoomframe/)
* کلاس [ISection](../../isection/)
* کلاس [ShapeCollection](../)
* کلاس [IPPImage](../../ippimage/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)