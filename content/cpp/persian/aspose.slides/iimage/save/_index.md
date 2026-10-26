---
title: Save()
second_title: مرجع API Aspose.Slides برای C++
description: تصویر را در یک فایل ذخیره می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides/iimage/save/
---
## IImage::Save(System::String) متد

تصویر را در یک فایل ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | مسیر فایلی که تصویر در آن ذخیره خواهد شد. |

## IImage::Save(System::String, ImageFormat) متد

تصویر را در یک فایل با فرمت مشخص ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | مسیر فایلی که تصویر در آن ذخیره خواهد شد. |
| format | [ImageFormat](../../imageformat/) | فرمت تصویر. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) متد

تصویر را در یک استریم با فرمت مشخص ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | استریمی که تصویر در آن ذخیره خواهد شد. |
| format | [ImageFormat](../../imageformat/) | فرمت تصویر. |

## IImage::Save(System::String, ImageFormat, int32_t) متد

تصویر را در یک فایل با فرمت و کیفیت مشخص ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | مسیر فایلی که تصویر در آن ذخیره خواهد شد. |
| format | [ImageFormat](../../imageformat/) | فرمت تصویر. |
| quality | **int32_t** | کیفیت تصویر ذخیره‌شده (۰ تا ۱۰۰).  

 این پارامتر تنها بر ذخیره‌سازی در [ImageFormat::Jpeg](../../imageformat/) تأثیر می‌گذارد؛ برای سایر فرمت‌ها نادیده گرفته می‌شود. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) متد

تصویر را در یک استریم با فرمت و کیفیت مشخص ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | استریمی که تصویر در آن ذخیره خواهد شد. |
| format | [ImageFormat](../../imageformat/) | فرمت تصویر. |
| quality | **int32_t** | کیفیت تصویر ذخیره‌شده (۰ تا ۱۰۰).  

 این پارامتر تنها بر ذخیره‌سازی در [ImageFormat::Jpeg](../../imageformat/) تأثیر می‌گذارد؛ برای سایر فرمت‌ها نادیده گرفته می‌شود. |

## موارد مرتبط

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IImage](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)