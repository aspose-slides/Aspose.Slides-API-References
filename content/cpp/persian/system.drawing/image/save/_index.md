---
title: Save()
second_title: Aspose.Slides برای C++ مرجع API
description: تصویر نمایش داده شده توسط شیء جاری را در فرمت PNG به فایل مشخص شده ذخیره می‌کند.
type: docs
weight: 1
url: /fa/system.drawing/image/save/
---
## Image::Save(const String\&) متد

تصویر نمایش داده شده توسط شیء جاری را در فرمت PNG به فایل مشخص شده ذخیره می‌کند.

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | نام فایلی که تصویر در آن ذخیره می‌شود |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) متد

تصویر نمایش داده شده توسط شیء جاری را در فرمت مشخص به فایل مشخص شده ذخیره می‌کند.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | نام فایلی که تصویر در آن ذخیره می‌شود |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | فرمت مورد استفاده برای ذخیره تصویر |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) متد

تصویر نمایش داده شده توسط شیء جاری را در فرمت مشخص به جریان مشخص شده ذخیره می‌کند.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | جریانی که تصویر در آن ذخیره می‌شود |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | فرمت مورد استفاده برای ذخیره تصویر |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) متد

تصویر نمایش داده شده توسط شیء جاری را با انکودر و پارامترهای انکودر مشخص به فایل مشخص ذخیره می‌کند.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | نام فایلی که تصویر در آن ذخیره می‌شود |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | انکودری که استفاده می‌شود |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | پارامترهای انکودر مورد استفاده |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) متد

تصویر نمایش داده شده توسط شیء جاری را با انکودر و پارامترهای انکودر مشخص به جریان مشخص ذخیره می‌کند.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | جریانی که تصویر در آن ذخیره می‌شود |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | انکودری که استفاده می‌شود |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | پارامترهای انکودر مورد استفاده |

## موارد مرتبط

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* کلاس [String](../../../system/string/)
* کلاس [Image](../)
* کلاس [Stream](../../../system.io/stream/)
* فضای نام [System::Drawing](../../)
* کتابخانه [Aspose.Slides](../../../)