---
title: InsertSectionZoomFrame()
second_title: مرجع API Aspose.Slides برای C++
description: یک قاب Zoom Section جدید ایجاد می‌کند و آن را در مجموعه شکل‌ها در اندیس مشخص شده وارد می‌کند.
type: docs
weight: 131
url: /fa/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) متد

یک قاب زوم [Section](../../section/) جدید ایجاد می‌کند و آن را در مجموعه شکل‌ها در اندیس مشخص شده وارد می‌کند.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفرپایه‌ای که [Section](../../section/) Zoom frame باید در آن وارد شود. |
| x | **float** | مختصات x قاب زوم [Section](../../section/) جدید، به واحد نقطه. |
| y | **float** | مختصات y قاب زوم [Section](../../section/) جدید، به واحد نقطه. |
| width | **float** | عرض قاب زوم [Section](../../section/) جدید، به نقطه. |
| height | **float** | ارتفاع قاب زوم [Section](../../section/) جدید، به نقطه. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) که توسط قاب زوم [Section](../../section/) ارجاع داده شده؛ باید متعلق به این پرزنتیشن باشد و حداقل شامل یک اسلاید باشد. |

### مقدار بازگشتی

[ISectionZoomFrame](../../isectionzoomframe/) تازه ایجاد شده.

## ملاحظات

این مثال نحوه ایجاد و وارد کردن یک شیء زوم [Section](../../section/) را در اندیس مشخص‌شده یک مجموعه نشان می‌دهد (فرض کنید در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) متد

یک قاب زوم [Section](../../section/) جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در مجموعه شکل‌ها در اندیس مشخص شده وارد می‌کند.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفرپایه‌ای که [Section](../../section/) Zoom frame باید در آن وارد شود. |
| x | **float** | مختصات x قاب زوم [Section](../../section/) جدید، به واحد نقطه. |
| y | **float** | مختصات y قاب زوم [Section](../../section/) جدید، به واحد نقطه. |
| width | **float** | عرض قاب زوم [Section](../../section/) جدید، به نقطه. |
| height | **float** | ارتفاع قاب زوم [Section](../../section/) جدید، به نقطه. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) که توسط قاب زوم [Section](../../section/) ارجاع داده شده؛ باید متعلق به این پرزنتیشن باشد و حداقل شامل یک اسلاید باشد. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | تصویری که در داخل قاب زوم [Section](../../section/) نمایش داده می‌شود. |

### مقدار بازگشتی

[ISectionZoomFrame](../../isectionzoomframe/) تازه ایجاد شده.

## ملاحظات

این مثال نحوه ایجاد و وارد کردن یک شیء زوم [Section](../../section/) را در اندیس مشخص‌شده یک مجموعه نشان می‌دهد (فرض کنید در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)