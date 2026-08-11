---
title: AddZoomFrame()
second_title: مرجع API Aspose.Slides برای C++
description: یک فریم زوم جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند.
type: docs
weight: 105
url: /fa/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) متد

یک فریم زوم جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم زوم جدید، بر حسب نقطه. |
| y | **float** | مختصات y فریم زوم جدید، بر حسب نقطه. |
| width | **float** | عرض فریم زوم جدید، بر حسب نقطه. |
| height | **float** | ارتفاع فریم زوم جدید، بر حسب نقطه. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) ارجاع شده توسط فریم زوم؛ باید متعلق به این ارائه باشد. |

### مقدار بازگشت

‏[IZoomFrame](../../izoomframe/) جدید ایجاد شده.

## ملاحظات

این مثال افزودن یک شیء Zoom به انتهای یک مجموعه را نشان می‌دهد (در نظر بگیرید که حداقل دو اسلاید در ارائه "Presentation.pptx" وجود دارد):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) متد


یک فریم زوم جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم زوم جدید، بر حسب نقطه. |
| y | **float** | مختصات y فریم زوم جدید، بر حسب نقطه. |
| width | **float** | عرض فریم زوم جدید، بر حسب نقطه. |
| height | **float** | ارتفاع فریم زوم جدید، بر حسب نقطه. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) ارجاع شده توسط فریم زوم؛ باید متعلق به این ارائه باشد. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | تصویر برای اسلاید ارجاع شده [IPPImage](../../ippimage/). |

### مقدار بازگشت

‏[IZoomFrame](../../izoomframe/) جدید ایجاد شده.

## ملاحظات

این مثال افزودن یک شیء Zoom به انتهای یک مجموعه را نشان می‌دهد (در نظر بگیرید که حداقل دو اسلاید در ارائه "Presentation.pptx" وجود دارد):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IZoomFrame](../../izoomframe/)
* کلاس [ISlide](../../islide/)
* کلاس [ShapeCollection](../)
* کلاس [IPPImage](../../ippimage/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)