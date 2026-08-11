---
title: GetImage()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شی تصویر با مقیاس‌گذاری سفارشی برمی‌گرداند.
type: docs
weight: 105
url: /fa/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) متد

یک شی تصویر با مقیاس‌گذاری سفارشی برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| scaleX | **float** | مقداری که برای تغییر مقیاس این Thumbnail در جهت محور x استفاده می‌شود. |
| scaleY | **float** | مقداری که برای تغییر مقیاس این Thumbnail در جهت محور y استفاده می‌شود. |

### مقدار بازگشتی

شی تصویر [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() متد

یک شی تصویر Thumbnail (20٪ از اندازه واقعی) برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### مقدار بازگشتی

شی تصویر [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) متد

یک شی تصویر با اندازه مشخص برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | اندازه تصویر برای ساخت. |

### مقدار بازگشتی

شی بیت‌مپ.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) متد

یک شی بیت‌مپ tiff Thumbnail با پارامترهای مشخص برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | گزینه‌های tiff. |

### مقدار بازگشتی

شی تصویر.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) متد

یک شی Bitmap Thumbnail برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |

### مقدار بازگشتی

اشیای Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) متد

یک شی Bitmap Thumbnail با مقیاس‌گذاری سفارشی برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |
| scaleX | **float** | مقداری که برای تغییر مقیاس این Thumbnail در جهت محور x استفاده می‌شود. |
| scaleY | **float** | مقداری که برای تغییر مقیاس این Thumbnail در جهت محور y استفاده می‌شود. |

### مقدار بازگشتی

اشیای Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) متد

یک شی Bitmap Thumbnail با اندازه مشخص برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | اندازه تصویر برای ساخت. |

### مقدار بازگشتی

اشیای Bitmap.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IImage](../../iimage/)
* کلاس [ISlide](../)
* کلاس [Size](../../../system.drawing/size/)
* کلاس [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* کلاس [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)