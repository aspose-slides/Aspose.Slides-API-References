---
title: AddImage()
second_title: Aspose.Slides برای C++ مرجع API
description: یک تصویر را به ارائه اضافه می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) متد

یک تصویر را به ارائه اضافه می‌کند.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | تصویر برای افزودن. |

### مقدار بازگشت

تصویر افزوده شد.

## توضیحات

این متد پرونده‌های متافایل WMF/EMF را قبل از درج در ارائه به تصویر PNG رستر تبدیل می‌کند.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) متد

تصویر را از یک جریان حافظه اضافه می‌کند.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | جریان حافظه. |

### مقدار بازگشت

تصویر افزوده شد.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) متد

یک تصویر را از جریان به ارائه اضافه می‌کند.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان برای افزودن تصویر. |

### مقدار بازگشت

تصویر افزوده شد.

## توضیحات

این متد می‌تواند پرونده‌های متافایل WMF/EMF را بدون تبدیل به تصویر PNG رستر به ارائه اضافه کند.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) متد

یک تصویر را از جریان ایجاد و به ارائه اضافه می‌کند.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان برای افزودن فایل تصویر. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | رفتار اعمال‌شده به جریان. |

### مقدار بازگشت

[IPPImage](../../ippimage/) افزوده شد.

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) متد

یک تصویر را از بافر مشخص به ارائه اضافه می‌کند.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافر. |

### مقدار بازگشت

تصویر افزوده شد.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) متد

یک نسخه از تصویر را از ارائه دیگر اضافه می‌کند.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | تصویر منبع. |

### مقدار بازگشت

تصویر افزوده شد.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) متد

یک تصویر را از شی SVG به ارائه اضافه می‌کند.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | شی تصویر SVG [ISvgImage](../../isvgimage/) |

### مقدار بازگشت

تصویر افزوده شد.

## همچنین ببینید

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [IImage](../../iimage/)
* Class [IImageCollection](../)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)