---
title: GetImages()
second_title: مرجع API Aspose.Slides برای C++
description: یک شی Image برای تمام اسلایدهای یک ارائه برمی‌گرداند.
type: docs
weight: 456
url: /fa/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) متد

یک شی Image برای تمام اسلایدهای یک ارائه برمی‌گرداند.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های Tiff. |

### مقدار بازگشت

اشیاء Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) متد

یک شی Thumbnail Image برای اسلایدهای مشخص شدهٔ یک ارائه برمی‌گرداند.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | آرایه‌ای از موقعیت‌های اسلاید، شروع از 1. |

### مقدار بازگشت

اشیاء Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) متد

یک شی Thumbnail Image برای تمام اسلایدهای یک ارائه با مقیاس‌گذاری سفارشی برمی‌گرداند.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های Tiff. |
| scaleX | **float** | مقداری که برای مقیاس‌گذاری این Thumbnail در جهت محور x استفاده می‌شود. |
| scaleY | **float** | مقداری که برای مقیاس‌گذاری این Thumbnail در جهت محور y استفاده می‌شود. |

### مقدار بازگشت

اشیاء Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) متد

یک شی Thumbnail Image برای اسلایدهای مشخص شدهٔ یک ارائه با مقیاس‌گذاری سفارشی برمی‌گرداند.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | آرایه‌ای از موقعیت‌های اسلاید، شروع از 1. |
| scaleX | **float** | مقداری که برای مقیاس‌گذاری این Thumbnail در جهت محور x استفاده می‌شود. |
| scaleY | **float** | مقداری که برای مقیاس‌گذاری این Thumbnail در جهت محور y استفاده می‌شود. |

### مقدار بازگشت

اشیاء Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) متد

یک شی Thumbnail Image برای تمام اسلایدهای یک ارائه با اندازهٔ مشخص برمی‌گرداند.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های Tiff. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | اندازهٔ تصویری که باید ایجاد شود. |

### مقدار بازگشت

اشیاء Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) متد

یک شی Thumbnail Image برای اسلایدهای مشخص شدهٔ یک ارائه با اندازهٔ مشخص برمی‌گرداند.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | آرایه‌ای از موقعیت‌های اسلاید، شروع از 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | اندازهٔ تصویری که باید ایجاد شود. |

### مقدار بازگشت

اشیاء Image.

## همچنین ببینید

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IImage](../../iimage/)
* کلاس [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* کلاس [Presentation](../)
* کلاس [Size](../../../system.drawing/size/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)