---
title: ReadPresentation()
second_title: Aspose.Slides برای مرجع API C++
description: یک ارائه موجود را از آرایه می‌خواند
type: docs
weight: 40
url: /fa/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) متد

یک ارائه موجود را از آرایه می‌خواند

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه برای خواندن |

### مقدار بازگشت

ارائه خوانده شده

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) متد

یک ارائه موجود را از آرایه با گزینه‌های بارگذاری اضافی می‌خواند

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه برای خواندن |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | گزینه‌های بارگذاری |

### مقدار بازگشت

ارائه خوانده شده

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) متد

یک ارائه موجود را از جریان می‌خواند

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان ورودی برای خواندن |

### مقدار بازگشت

ارائه خوانده شده

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) متد

یک ارائه موجود را از جریان با گزینه‌های بارگذاری اضافی می‌خواند

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان ورودی برای خواندن |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | گزینه‌های بارگذاری |

### مقدار بازگشت

ارائه خوانده شده

## PresentationFactory::ReadPresentation(System::String) متد

یک ارائه موجود را از فایل می‌خواند

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | نام فایل |

### مقدار بازگشت

ارائه خوانده شده

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) متد

یک ارائه موجود را از فایل با گزینه‌های بارگذاری اضافی می‌خواند

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | نام فایل |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | گزینه‌های بارگذاری |

### مقدار بازگشت

ارائه خوانده شده

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [IPresentation](../../ipresentation/)
* کلاس [PresentationFactory](../)
* کلاس [ILoadOptions](../../iloadoptions/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)