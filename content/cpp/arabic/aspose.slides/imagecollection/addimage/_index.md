---
title: AddImage()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف نسخة من صورة من عرض تقديمي آخر.
type: docs
weight: 53
url: /ar/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) طريقة


يضيف نسخة من صورة من عرض تقديمي آخر.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | الصورة المصدر. |

### قيمة الإرجاع

الصورة المضافة.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) طريقة


إضافة صورة إلى عرض تقديمي.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | الصورة التي سيتم إضافتها. |

### قيمة الإرجاع

الصورة المضافة.
## ملاحظات


تحول هذه الطريقة ملفات WMF/EMF الميتافيل إلى صورة PNG نقطية قبل إدراجها في عرض تقديمي.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) طريقة


إضافة صورة إلى عرض تقديمي من تدفق.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | التدفق لإضافة الصورة منه. |

### قيمة الإرجاع

الصورة المضافة.
## ملاحظات


يمكن لهذه الطريقة إضافة ملفات WMF/EMF الميتافيل إلى عرض تقديمي دون تحويلها إلى صورة PNG نقطية.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) طريقة


إضافة صورة إلى عرض تقديمي من تدفق.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | التدفق لإضافة الصورة منه. |

### قيمة الإرجاع

الصورة المضافة.
## ملاحظات


يمكن لهذه الطريقة إضافة ملفات WMF/EMF الميتافيل إلى عرض تقديمي دون تحويلها إلى صورة PNG نقطية.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) طريقة


ينشئ ويضيف صورة إلى عرض تقديمي من تدفق.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | التدفق لإضافة ملف الصورة منه. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | السلوك الذي سيتم تطبيقه على التدفق. |

### قيمة الإرجاع

تمت إضافة [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) طريقة


يضيف صورة إلى عرض تقديمي من المخزن المؤقت المحدد.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن المؤقت. |

### قيمة الإرجاع

الصورة المضافة.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) طريقة


إضافة صورة إلى عرض تقديمي من كائن Svg.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | كائن صورة Svg [ISvgImage](../../isvgimage/) |

### قيمة الإرجاع

الصورة المضافة.

## انظر أيضًا

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [ImageCollection](../)
* Class [IImage](../../iimage/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)