---
title: Presentation()
second_title: مرجع API Aspose.Slides برای C++
description: این سازنده یک ارائه جدید را از ابتدا ایجاد می‌کند. ارائهٔ ایجاد شده شامل یک اسلاید خالی است.
type: docs
weight: 417
url: /fa/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() سازنده

این سازنده یک ارائه جدید را از ابتدا ایجاد می‌کند. ارائهٔ ایجاد شده شامل یک اسلاید خالی است.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) سازنده

این سازنده یک ارائه جدید را از ابتدا ایجاد می‌کند. ارائهٔ ایجاد شده شامل یک اسلاید خالی است.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | گزینه‌های بارگذاری اضافی. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) سازنده

این سازنده مکانیزم اصلی برای خواندن یک [Presentation](../) موجود است.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان ورودی. |

## توضیحات

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) سازنده

این سازنده مکانیزم اصلی برای خواندن یک [Presentation](../) موجود است.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان ورودی. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | گزینه‌های بارگذاری اضافی. |

## Presentation::Presentation(System::String) سازنده

این سازنده مسیر فایل منبع را دریافت می‌کند که محتویات [Presentation](../) از آن خوانده می‌شود.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | فایل ورودی. |

## توضیحات

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) سازنده

این سازنده مسیر فایل منبع را دریافت می‌کند که محتویات [Presentation](../) از آن خوانده می‌شود.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | فایل ورودی. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | گزینه‌های بارگذاری اضافی. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Presentation](../)
* کلاس [LoadOptions](../../loadoptions/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [String](../../../system/string/)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)