---
title: GetImages()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد كائنات Thumbnail Image لجميع شرائح العرض التقديمي.
type: docs
weight: 417
url: /ar/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) طريقة

يرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات التقديم. |

### قيمة الإرجاع

كائنات Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) طريقة

يرجع كائنات Bitmap مصغرة للشرائح المحددة في العرض التقديمي.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات التقديم. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | مصفوفة بمواقع الشرائح، تبدأ من 1. |

### قيمة الإرجاع

كائنات Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) طريقة

يرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي مع تكبير مخصص.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات التقديم. |
| scaleX | **float** | القيمة التي يتم بموجبها تكبير هذه الصورة المصغرة في اتجاه المحور x. |
| scaleY | **float** | القيمة التي يتم بموجبها تكبير هذه الصورة المصغرة في اتجاه المحور y. |

### قيمة الإرجاع

كائنات Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) طريقة

يرجع كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي مع تكبير مخصص.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات التقديم. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| scaleX | **float** | القيمة التي يتم بموجبها تكبير هذه الصورة المصغرة في اتجاه المحور x. |
| scaleY | **float** | القيمة التي يتم بموجبها تكبير هذه الصورة المصغرة في اتجاه المحور y. |

### قيمة الإرجاع

كائنات Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) طريقة

يرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي بالحجم المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات التقديم. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | حجم الصورة التي سيتم إنشاؤها. |

### قيمة الإرجاع

كائنات Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) طريقة

يرجع كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي بالحجم المحدد.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات التقديم. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | حجم الصورة التي سيتم إنشاؤها. |

### قيمة الإرجاع

كائنات Bitmap.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IImage](../../iimage/)
* فئة [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* فئة [IPresentation](../)
* فئة [Size](../../../system.drawing/size/)
* مساحة أسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)