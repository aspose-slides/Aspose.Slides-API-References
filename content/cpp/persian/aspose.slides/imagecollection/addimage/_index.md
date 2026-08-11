---
title: AddImage()
second_title: Aspose.Slides برای مرجع API C++
description: یک نسخه از تصویر را از یک ارائه دیگر اضافه می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) متد


یک نسخه از تصویر را از یک ارائهٔ دیگر اضافه می‌کند.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | تصویر منبع. |

### مقدار بازگشت

تصویر اضافه شده.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) متد


یک تصویر به یک ارائه اضافه می‌کند.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | تصویری که باید اضافه شود. |

### مقدار بازگشت

تصویر اضافه شده.

## توضیحات


این متد قبل از افزودن به یک ارائه، فایل‌های متافایل WMF/EMF را به تصویر PNG شطرنجی (raster) تبدیل می‌کند.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) متد


یک تصویر را از جریان (stream) به یک ارائه اضافه می‌کند.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | جریانی که تصویر از آن اضافه می‌شود. |

### مقدار بازگشت

تصویر اضافه شده.

## توضیحات


این متد می‌تواند فایل‌های متافایل WMF/EMF را به ارائه اضافه کند بدون آنکه آنها را به تصویر PNG شطرنجی تبدیل کند.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) متد


یک تصویر را از جریان (stream) به یک ارائه اضافه می‌کند.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریانی که تصویر از آن اضافه می‌شود. |

### مقدار بازگشت

تصویر اضافه شده.

## توضیحات


این متد می‌تواند فایل‌های متافایل WMF/EMF را به ارائه اضافه کند بدون آنکه آنها را به تصویر PNG شطرنجی تبدیل کند.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) متد


یک تصویر را از جریان (stream) ایجاد و به یک ارائه اضافه می‌کند.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریانی که فایل تصویر از آن خوانده می‌شود. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | رفتاری که بر روی جریان اعمال می‌شود. |

### مقدار بازگشت

[IPPImage](../../ippimage/) اضافه شده.

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) متد


یک تصویر را از بافر مشخص به یک ارائه اضافه می‌کند.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافر. |

### مقدار بازگشت

تصویر اضافه شده.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) متد


یک تصویر را از شیء Svg به یک ارائه اضافه می‌کند.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | شیء تصویر Svg [ISvgImage](../../isvgimage/) |

### مقدار بازگشت

تصویر اضافه شده.

## موارد مرتبط

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