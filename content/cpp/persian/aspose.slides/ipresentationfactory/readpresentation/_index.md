---
title: ReadPresentation()
second_title: مرجع API Aspose.Slides برای C++
description: یک ارائه موجود را از آرایه می‌خواند
type: docs
weight: 27
url: /fa/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) متد

یک ارائه موجود را از آرایه می‌خواند

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه برای خواندن |

### مقدار بازگشت

ارائه خوانده شده

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) متد

یک ارائه موجود را از آرایه با گزینه‌های بارگذاری اضافی می‌خواند

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه برای خواندن |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | گزینه‌های بارگذاری |

### مقدار بازگشت

ارائه خوانده شده

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) متد

یک ارائه موجود را از جریان می‌خواند

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان ورودی برای خواندن |

### مقدار بازگشت

ارائه خوانده شده

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) متد

یک ارائه موجود را از جریان با گزینه‌های بارگذاری اضافی می‌خواند

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان ورودی برای خواندن |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | گزینه‌های بارگذاری |

### مقدار بازگشت

ارائه خوانده شده

## IPresentationFactory::ReadPresentation(System::String) متد

یک ارائه موجود را از فایل می‌خواند

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | نام فایل |

### مقدار بازگشت

ارائه خوانده شده

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) متد

یک ارائه موجود را از فایل با گزینه‌های بارگذاری اضافی می‌خواند

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | نام فایل |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | گزینه‌های بارگذاری |

### مقدار بازگشت

ارائه خوانده شده

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [IPresentation](../../ipresentation/)
* کلاس [IPresentationFactory](../)
* کلاس [ILoadOptions](../../iloadoptions/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [String](../../../system/string/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)