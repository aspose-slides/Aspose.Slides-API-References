---
title: GetImage()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد كائن صورة مع تحجيم مخصص.
type: docs
weight: 105
url: /ar/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) طريقة

يعيد كائن Image مع تحجيم مخصص.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| scaleX | **float** | القيمة التي سيتم بموجبها تحجيم هذه المصغرة في اتجاه محور x. |
| scaleY | **float** | القيمة التي سيتم بموجبها تحجيم هذه المصغرة في اتجاه محور y. |

### قيمة الإرجاع

كائن Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() طريقة

يعيد كائن Thumbnail Image (20% من الحجم الحقيقي).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### قيمة الإرجاع

كائن Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) طريقة

يعيد كائن Image بالحجم المحدد.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | حجم الصورة التي سيتم إنشاؤها. |

### قيمة الإرجاع

كائن Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) طريقة

يعيد كائن تيف Bitmap مصغر مع المعلمات المحددة.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | خيارات tiff. |

### قيمة الإرجاع

كائن Image.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) طريقة

يعيد كائن Thumbnail Bitmap.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات التصيير. |

### قيمة الإرجاع

كائنات Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) طريقة

يعيد كائن Thumbnail Bitmap مع تحجيم مخصص.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات التصيير. |
| scaleX | **float** | القيمة التي سيتم بموجبها تحجيم هذه المصغرة في اتجاه محور x. |
| scaleY | **float** | القيمة التي سيتم بموجبها تحجيم هذه المصغرة في اتجاه محور y. |

### قيمة الإرجاع

كائنات Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) طريقة

يعيد كائن Thumbnail Bitmap بالحجم المحدد.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات التصيير. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | حجم الصورة التي سيتم إنشاؤها. |

### قيمة الإرجاع

كائنات Bitmap.

## راجع أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)