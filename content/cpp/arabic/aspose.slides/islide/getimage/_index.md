---
title: GetImage()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع كائن صورة مع تحجيم مخصص.
type: docs
weight: 105
url: /ar/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) طريقة

إرجاع كائن Image مع تحجيم مخصص.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| scaleX | **float** | القيمة التي يتم من خلالها تحجيم هذا Thumbnail في اتجاه محور x. |
| scaleY | **float** | القيمة التي يتم من خلالها تحجيم هذا Thumbnail في اتجاه محور y. |

### قيمة الإرجاع

كائن Image [IImage](../../iimage/)

## ISlide::GetImage() طريقة

إرجاع كائن Thumbnail Image (20% من الحجم الحقيقي).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### قيمة الإرجاع

كائن Image [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) طريقة

إرجاع كائن Image بالحجم المحدد.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | حجم الصورة لإنشائها. |

### قيمة الإرجاع

كائن Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) طريقة

إرجاع كائن Thumbnail tiff bitmap بالمعلمات المحددة.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | خيارات Tiff. |

### قيمة الإرجاع

كائن Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) طريقة

إرجاع كائن Thumbnail Bitmap.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات Rendering. |

### قيمة الإرجاع

كائن Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) طريقة

إرجاع كائن Thumbnail Bitmap مع تحجيم مخصص.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات Rendering. |
| scaleX | **float** | القيمة التي يتم من خلالها تحجيم هذا Thumbnail في اتجاه محور x. |
| scaleY | **float** | القيمة التي يتم من خلالها تحجيم هذا Thumbnail في اتجاه محور y. |

### قيمة الإرجاع

كائن Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) طريقة

إرجاع كائن Thumbnail Bitmap بالحجم المحدد.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات Rendering. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | حجم الصورة لإنشائها. |

### قيمة الإرجاع

كائن Image [IImage](../../iimage/)

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IImage](../../iimage/)
* فئة [ISlide](../)
* فئة [Size](../../../system.drawing/size/)
* فئة [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* فئة [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)