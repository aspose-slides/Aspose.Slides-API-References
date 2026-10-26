---
title: AddSectionZoomFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: یک فریم Zoom جدید برای بخش ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند.
type: docs
weight: 118
url: /fa/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) متد

یک فریم Zoom جدید [Section](../../section/) ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم Zoom جدید [Section](../../section/)، بر حسب پوینت. |
| y | **float** | مختصات y فریم Zoom جدید [Section](../../section/)، بر حسب پوینت. |
| width | **float** | عرض فریم Zoom جدید [Section](../../section/)، بر حسب پوینت. |
| height | **float** | ارتفاع فریم Zoom جدید [Section](../../section/)، بر حسب پوینت. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) که توسط فریم Zoom [Section](../../section/) ارجاع می‌شود؛ باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |

### Return Value

[ISectionZoomFrame](../../isectionzoomframe/) تازه ایجاد شده.

## Remarks

این مثال نشان می‌دهد که چگونه یک شیء Zoom [Section](../../section/) را به انتهای یک مجموعه اضافه می‌کنیم (فرض کنید در ارائهٔ \"Presentation.pptx\" حداقل دو بخش وجود دارد): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) متد

یک فریم Zoom جدید [Section](../../section/) با تصویری از پیش تعریف شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم Zoom جدید [Section](../../section/)، بر حسب پوینت. |
| y | **float** | مختصات y فریم Zoom جدید [Section](../../section/)، بر حسب پوینت. |
| width | **float** | عرض فریم Zoom جدید [Section](../../section/)، بر حسب پوینت. |
| height | **float** | ارتفاع فریم Zoom جدید [Section](../../section/)، بر حسب پوینت. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) که توسط فریم Zoom [Section](../../section/) ارجاع می‌شود؛ باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) برای نمایش در داخل فریم Zoom [Section](../../section/). |

### Return Value

[ISectionZoomFrame](../../isectionzoomframe/) تازه ایجاد شده.

## Remarks

این مثال نشان می‌دهد که چگونه یک شیء Zoom [Section](../../section/) را به انتهای یک مجموعه اضافه می‌کنیم (فرض کنید در ارائهٔ \"Presentation.pptx\" حداقل دو بخش وجود دارد): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISectionZoomFrame](../../isectionzoomframe/)
* کلاس [ISection](../../isection/)
* کلاس [IShapeCollection](../)
* کلاس [IPPImage](../../ippimage/)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)