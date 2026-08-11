---
title: Process()
second_title: مرجع API Aspose.Slides برای C++
description: چندین ارائهٔ پاورپوینت با فرمت یکسان را در یک فایل ارائهٔ واحد ترکیب می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) متد

چندین ارائهٔ پاورپوینت با فرمت یکسان را در یک فایل ارائهٔ واحد ترکیب می‌کند.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | یک آرایه از نام‌های فایل‌های ارائهٔ ورودی. |
| outputFileName | [System::String](../../../system/string/) | نام فایل خروجی فایل ارائهٔ ترکیب‌شده. |
## توضیحات

```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) متد

چندین ارائهٔ پاورپوینت با فرمت یکسان را در یک فایل ارائهٔ واحد ترکیب می‌کند.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | یک آرایه از نام‌های فایل‌های ارائهٔ ورودی. |
| outputFileName | [System::String](../../../system/string/) | نام فایل خروجی فایل ارائهٔ ترکیب‌شده. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | گزینه‌های اضافی که تعیین می‌کنند ارائهٔ ترکیب‌شده چگونه ذخیره شود. |
## توضیحات

```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) متد

چندین ارائهٔ پاورپوینت با فرمت یکسان را در یک فایل ارائهٔ واحد ترکیب می‌کند.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | یک آرایه از نام‌های فایل‌های ارائهٔ ورودی. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان خروجی. |
## توضیحات

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) متد

چندین ارائهٔ پاورپوینت با فرمت یکسان را در یک فایل ارائهٔ واحد ترکیب می‌کند.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | یک آرایه از نام‌های فایل‌های ارائهٔ ورودی. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان خروجی. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | گزینه‌های اضافی که تعیین می‌کنند ارائهٔ ترکیب‌شده چگونه ذخیره شود. |
## توضیحات

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## موارد مرتبط

* نوع‌تعریف [ArrayPtr](../../../system/arrayptr/)
* نوع‌تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [Merger](../)
* کلاس [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* کلاس [Stream](../../../system.io/stream/)
* فضای‌نام [Aspose::Slides::LowCode](../../)
* کتابخانه [Aspose.Slides](../../../)