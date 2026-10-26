---
title: AddZoomFrame()
second_title: مرجع API Aspose.Slides برای C++
description: یک فریم زوم جدید ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌سازد.
type: docs
weight: 92
url: /fa/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) متد


یک فریم زوم جدید ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌‍سازد.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم زوم جدید، بر حسب نقطه. |
| y | **float** | مختصات y فریم زوم جدید، بر حسب نقطه. |
| width | **float** | عرض فریم زوم جدید، بر حسب نقطه. |
| height | **float** | ارتفاع فریم زوم جدید، بر حسب نقطه. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) ای که توسط فریم زوم ارجاع شده است؛ باید متعلق به این ارائه باشد. |

### مقدار بازگشت

[IZoomFrame](../../izoomframe/) تازه ساخته شده.

## توضیحات


این مثال نشان می‌دهد که چگونه یک شی Zoom را به انتهای یک مجموعه اضافه کنیم (فرض کنید که در ارائه "Presentation.pptx" حداقل دو اسلاید وجود دارد): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) متد


یک فریم زوم جدید ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می-سازد.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات x فریم زوم جدید، بر حسب نقطه. |
| y | **float** | مختصات y فریم زوم جدید، بر حسب نقطه. |
| width | **float** | عرض فریم زوم جدید، بر حسب نقطه. |
| height | **float** | ارتفاع فریم زوم جدید، بر حسب نقطه. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) ای که توسط فریم زوم ارجاع شده است؛ باید متعلق به این ارائه باشد. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | تصویر برای اسلاید ارجاع شده [IPPImage](../../ippimage/). |

### مقدار بازگشت

[IZoomFrame](../../izoomframe/) تازه ساخته شده.

## توضیحات


این مثال نشان می‌دهد که چگونه یک شی Zoom را به انتهای یک مجموعه اضافه کنیم (فرض کنید که در ارائه "Presentation.pptx" حداقل دو اسلاید وجود دارد): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## نیز ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)