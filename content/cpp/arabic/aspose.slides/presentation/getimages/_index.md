---
title: GetImages()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد كائنات Image لجميع الشرائح في العرض.
type: docs
weight: 456
url: /ar/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) طريقة

يعيد كائنات Image لجميع الشرائح في العرض.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات Tiff. |

### قيمة الإرجاع

كائنات Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) طريقة

يعيد كائنات Thumbnail Image للشرائح المحددة في العرض.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |

### قيمة الإرجاع

كائنات Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) طريقة

يعيد كائنات Thumbnail Image لجميع الشرائح في العرض مع تحجيم مخصص.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات Tiff. |
| scaleX | **float** | القيمة التي يتم بموجبها تحجيم هذا Thumbnail في اتجاه المحور x. |
| scaleY | **float** | القيمة التي يتم بموجبها تحجيم هذا Thumbnail في اتجاه المحور y. |

### قيمة الإرجاع

كائنات Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) طريقة

يعيد كائنات Thumbnail Image للشرائح المحددة في العرض مع تحجيم مخصص.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| scaleX | **float** | القيمة التي يتم بموجبها تحجيم هذا Thumbnail في اتجاه المحور x. |
| scaleY | **float** | القيمة التي يتم بموجبها تحجيم هذا Thumbnail في اتجاه المحور y. |

### قيمة الإرجاع

كائنات Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) طريقة

يعيد كائنات Thumbnail Image لجميع الشرائح في العرض بالحجم المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات Tiff. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | حجم الصورة التي سيتم إنشاؤها. |

### قيمة الإرجاع

كائنات Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) طريقة

يعيد كائنات Thumbnail Image للشرائح المحددة في العرض بالحجم المحدد.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | حجم الصورة التي سيتم إنشاؤها. |

### قيمة الإرجاع

كائنات Image.

## انظر أيضًا

* نوع معرف [ArrayPtr](../../../system/arrayptr/)
* نوع معرف [SharedPtr](../../../system/sharedptr/)
* فئة [IImage](../../iimage/)
* فئة [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* فئة [Presentation](../)
* فئة [Size](../../../system.drawing/size/)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)