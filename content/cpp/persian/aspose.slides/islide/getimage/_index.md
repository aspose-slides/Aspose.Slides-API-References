---
title: GetImage()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شیء تصویر با مقیاس‌گذاری سفارشی برمی‌گرداند.
type: docs
weight: 105
url: /fa/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) متد

یک شیء تصویر با مقیاس‌گذاری سفارشی برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### استدلال‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| scaleX | **float** | مقداری که برای مقیاس‌گذاری این بندانگشتی در جهت محور x استفاده می‌شود. |
| scaleY | **float** | مقداری که برای مقیاس‌گذاری این بندانگشتی در جهت محور y استفاده می‌شود. |

### مقدار برگشتی

شیء Image [IImage](../../iimage/)

## ISlide::GetImage() متد

یک شیء تصویر بندانگشتی (20٪ از اندازه واقعی) را برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### مقدار برگشتی

شیء Image [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) متد

یک شیء تصویر با اندازهٔ مشخص برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### استدلال‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | اندازهٔ تصویری که باید ایجاد شود. |

### مقدار برگشتی

شیء Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) متد

یک شیء بیتی‌مپ تِیف بندانگشتی با پارامترهای مشخص را برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### استدلال‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | گزینه‌های Tiff. |

### مقدار برگشتی

شیء Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) متد

یک شیء بیتی‌مپ بندانگشتی را برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### استدلال‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |

### مقدار برگشتی

شیء Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) متد

یک شیء بیتی‌مپ بندانگشتی با مقیاس‌گذاری سفارشی را برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### استدلال‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |
| scaleX | **float** | مقداری که برای مقیاس‌گذاری این بندانگشتی در جهت محور x استفاده می‌شود. |
| scaleY | **float** | مقداری که برای مقیاس‌گذاری این بندانگشتی در جهت محور y استفاده می‌شود. |

### مقدار برگشتی

شیء Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) متد

یک شیء بیتی‌مپ بندانگشتی با اندازهٔ مشخص را برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### استدلال‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | اندازهٔ تصویری که باید ایجاد شود. |

### مقدار برگشتی

شیء Image [IImage](../../iimage/)

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)