---
title: GetImages()
second_title: Aspose.Slides برای مرجع API C++
description: آبجکت‌های Thumbnail Image را برای تمام اسلایدهای یک ارائه برمی‌گرداند.
type: docs
weight: 417
url: /fa/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) متد

آبجکت‌های Thumbnail Image را برای تمام اسلایدهای یک ارائه برمی‌گرداند.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |

### مقدار بازگشت

آبجکت‌های Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) متد

آبجکت‌های Thumbnail Bitmap را برای اسلایدهای مشخص‌شده یک ارائه برمی‌گرداند.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | آرایه‌ای شامل موقعیت‌های اسلاید، شروع از 1. |

### مقدار بازگشت

آبجکت‌های Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) متد

آبجکت‌های Thumbnail Image را برای تمام اسلایدهای یک ارائه با مقیاس‌بندی سفارشی برمی‌گرداند.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |
| scaleX | **float** | مقداری که برای مقیاس‌بندی این Thumbnail در جهت محور x استفاده می‌شود. |
| scaleY | **float** | مقداری که برای مقیاس‌بندی این Thumbnail در جهت محور y استفاده می‌شود. |

### مقدار بازگشت

آبجکت‌های Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) متد

آبجکت‌های Thumbnail Image را برای اسلایدهای مشخص‌شده یک ارائه با مقیاس‌بندی سفارشی برمی‌گرداند.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | آرایه‌ای شامل موقعیت‌های اسلاید، شروع از 1. |
| scaleX | **float** | مقداری که برای مقیاس‌بندی این Thumbnail در جهت محور x استفاده می‌شود. |
| scaleY | **float** | مقداری که برای مقیاس‌بندی این Thumbnail در جهت محور y استفاده می‌شود. |

### مقدار بازگشت

آبجکت‌های Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) متد

آبجکت‌های Thumbnail Image را برای تمام اسلایدهای یک ارائه با اندازهٔ مشخص شده برمی‌گرداند.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | اندازهٔ تصویر برای ایجاد. |

### مقدار بازگشت

آبجکت‌های Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) متد

آبجکت‌های Thumbnail Image را برای اسلایدهای مشخص‌شده یک ارائه با اندازهٔ مشخص شده برمی‌گرداند.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | آرایه‌ای شامل موقعیت‌های اسلاید، شروع از 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | اندازهٔ تصویر برای ایجاد. |

### مقدار بازگشت

آبجکت‌های Bitmap.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [IPresentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)