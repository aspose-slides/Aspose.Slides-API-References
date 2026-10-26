---
title: InsertZoomFrame()
second_title: Aspose.Slides برای C++ - مرجع API
description: یک قاب Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص‌شده درج می‌نماید.
type: docs
weight: 118
url: /fa/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) متد

یک قاب Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص‌شده درج می‌نماید.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفرپایه‌ای که قاب Zoom در آن درج می‌شود. |
| x | **float** | مختصات x قاب Zoom جدید، بر حسب پوینت. |
| y | **float** | مختصات y قاب Zoom جدید، بر حسب پوینت. |
| width | **float** | عرض قاب Zoom جدید، بر حسب پوینت. |
| height | **float** | ارتفاع قاب Zoom جدید، بر حسب پوینت. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) که توسط قاب Zoom ارجاع شده است. |

### مقدار بازگشت

[IZoomFrame](../../izoomframe/) تازه ایجاد شده.

## نکات

این مثال ایجاد و درج یک شی Zoom را در اندیس مشخص‌شدهٔ یک مجموعه نشان می‌دهد (فرض کنید در ارائهٔ "Presentation.pptx" حداقل دو اسلاید وجود دارد): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) متد

یک قاب Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در اندیس مشخص‌شده درج می‌نماید.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفرپایه‌ای که قاب Zoom در آن درج می‌شود. |
| x | **float** | مختصات x قاب Zoom جدید، بر حسب پوینت. |
| y | **float** | مختصات y قاب Zoom جدید، بر حسب پوینت. |
| width | **float** | عرض قاب Zoom جدید، بر حسب پوینت. |
| height | **float** | ارتفاع قاب Zoom جدید، بر حسب پوینت. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) که توسط قاب Zoom ارجاع شده است. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | تصویر برای اسلاید ارجاع‌شده [IPPImage](../../ippimage/). |

### مقدار بازگشت

[IZoomFrame](../../izoomframe/) تازه ایجاد شده.

## نکات

این مثال ایجاد و درج یک شی Zoom را در اندیس مشخص‌شدهٔ یک مجموعه نشان می‌دهد (فرض کنید در ارائهٔ "Presentation.pptx" حداقل دو اسلاید وجود دارد): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IZoomFrame](../../izoomframe/)
* کلاس [ISlide](../../islide/)
* کلاس [ShapeCollection](../)
* کلاس [IPPImage](../../ippimage/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)