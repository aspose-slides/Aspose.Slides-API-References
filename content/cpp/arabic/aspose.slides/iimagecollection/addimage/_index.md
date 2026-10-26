---
title: AddImage()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: إضافة صورة إلى عرض تقديمي.
type: docs
weight: 14
url: /ar/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) طريقة

إضافة صورة إلى عرض تقديمي.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | الصورة المراد إضافتها. |

### قيمة الإرجاع

الصورة المضافة.

## ملاحظات

تحول هذه الطريقة ملفات WMF/EMF إلى صورة PNG نقطية قبل إدراجها في عرض تقديمي.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) طريقة

إضافة صورة من تدفق الذاكرة.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | تدفق الذاكرة. |

### قيمة الإرجاع

الصورة المضافة.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) طريقة

إضافة صورة إلى عرض تقديمي من التدفق.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | التدفق الذي ستُضاف الصورة منه. |

### قيمة الإرجاع

الصورة المضافة.

## ملاحظات

تستطيع هذه الطريقة إضافة ملفات WMF/EMF إلى عرض تقديمي دون تحويلها إلى صورة PNG نقطية.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) طريقة

إنشاء وإضافة صورة إلى عرض تقديمي من التدفق.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | التدفق الذي ستُضاف صورة الملف منه. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | السلوك الذي سيُطبق على التدفق. |

### قيمة الإرجاع

تمت إضافة [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) طريقة

إضافة صورة إلى عرض تقديمي من الذاكرة المؤقتة المحددة.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | الذاكرة المؤقتة. |

### قيمة الإرجاع

الصورة المضافة.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) طريقة

إضافة نسخة من صورة من عرض تقديمي آخر.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | صورة المصدر. |

### قيمة الإرجاع

الصورة المضافة.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) طريقة

إضافة صورة إلى عرض تقديمي من كائن SVG.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | كائن صورة SVG [ISvgImage](../../isvgimage/) |

### قيمة الإرجاع

الصورة المضافة.

## انظر أيضًا

* تعداد [LoadingStreamBehavior](../../loadingstreambehavior/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [IPPImage](../../ippimage/)
* فئة [IImage](../../iimage/)
* فئة [IImageCollection](../)
* فئة [MemoryStream](../../../system.io/memorystream/)
* فئة [Stream](../../../system.io/stream/)
* فئة [ISvgImage](../../isvgimage/)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)