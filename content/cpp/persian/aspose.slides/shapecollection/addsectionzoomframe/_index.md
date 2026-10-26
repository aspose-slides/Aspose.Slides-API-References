---
title: AddSectionZoomFrame()
second_title: مرجع API Aspose.Slides برای C++
description: یک فریم زوم Section جدید ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌کند.
type: docs
weight: 131
url: /fa/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) متد

یک فریم زوم جدید [Section](../../section/) ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم زوم جدید [Section](../../section/)، به نقطه. |
| y | **float** | مختصات y فریم زوم جدید [Section](../../section/)، به نقطه. |
| width | **float** | عرض فریم زوم جدید [Section](../../section/)، به نقطه. |
| height | **float** | ارتفاع فریم زوم جدید [Section](../../section/)، به نقطه. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) مورد ارجاع توسط فریم زوم [Section](../../section/)؛ باید به این ارائه تعلق داشته باشد و حداقل یک اسلاید داشته باشد. |

### مقدار بازگشت

[ISectionZoomFrame](../../isectionzoomframe/) جدید ایجاد شده.

## توضیحات

این مثال اضافه کردن یک شیء زوم [Section](../../section/) به انتهای یک مجموعه را نشان می‌دهد (فرض کنید که در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) متد

یک فریم زوم جدید [Section](../../section/) با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم زوم جدید [Section](../../section/)، به نقطه. |
| y | **float** | مختصات y فریم زوم جدید [Section](../../section/)، به نقطه. |
| width | **float** | عرض فریم زوم جدید [Section](../../section/)، به نقطه. |
| height | **float** | ارتفاع فریم زوم جدید [Section](../../section/)، به نقطه. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) مورد ارجاع توسط فریم زوم [Section](../../section/)؛ باید به این ارائه تعلق داشته باشد و حداقل یک اسلاید داشته باشد. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) جهت نمایش درون فریم زوم [Section](../../section/). |

### مقدار بازگشت

[ISectionZoomFrame](../../isectionzoomframe/) جدید ایجاد شده.

## توضیحات

این مثال اضافه کردن یک شیء زوم [Section](../../section/) به انتهای یک مجموعه را نشان می‌دهد (فرض کنید که در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISectionZoomFrame](../../isectionzoomframe/)
* کلاس [ISection](../../isection/)
* کلاس [ShapeCollection](../)
* کلاس [IPPImage](../../ippimage/)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)