---
title: InsertZoomFrame()
second_title: Aspose.Slides برای مرجع API C++
description: یک فریم Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده قرار می‌دهد.
type: docs
weight: 105
url: /fa/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) متد

یک فریم Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده قرار می‌دهد.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-محور که فریم Zoom در آن وارد می‌شود. |
| x | **float** | مختصات x فریم Zoom جدید، بر حسب پوینت. |
| y | **float** | مختصات y فریم Zoom جدید، بر حسب پوینت. |
| width | **float** | عرض فریم Zoom جدید، بر حسب پوینت. |
| height | **float** | ارتفاع فریم Zoom جدید، بر حسب پوینت. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) که توسط فریم Zoom ارجاع می‌شود. |

### مقدار بازگشت

[IZoomFrame](../../izoomframe/) جدید ایجاد شده.

## توضیحات

این مثال نشان می‌دهد که چگونه یک شی Zoom را ایجاد و در ایندکس مشخص شده از یک مجموعه وارد می‌کنیم (فرض کنید در ارائهٔ "Presentation.pptx" حداقل دو اسلاید وجود دارد):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) متد

یک فریم Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده قرار می‌دهد.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-محور که فریم Zoom در آن وارد می‌شود. |
| x | **float** | مختصات x فریم Zoom جدید، بر حسب پوینت. |
| y | **float** | مختصات y فریم Zoom جدید، بر حسب پوینت. |
| width | **float** | عرض فریم Zoom جدید، بر حسب پوینت. |
| height | **float** | ارتفاع فریم Zoom جدید، بر حسب پوینت. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) که توسط فریم Zoom ارجاع می‌شود. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | تصویر اسلاید ارجاع شده [IPPImage](../../ippimage/). |

### مقدار بازگشت

[IZoomFrame](../../izoomframe/) جدید ایجاد شده.

## توضیحات

این مثال نشان می‌دهد که چگونه یک شی Zoom را ایجاد و در ایندکس مشخص شده از یک مجموعه وارد می‌کنیم (فرض کنید در ارائهٔ "Presentation.pptx" حداقل دو اسلاید وجود دارد):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```


## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IZoomFrame](../../izoomframe/)
* کلاس [ISlide](../../islide/)
* کلاس [IShapeCollection](../)
* کلاس [IPPImage](../../ippimage/)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)