---
title: Save()
second_title: Aspose.Slides برای مرجع API C++
description: تمام اسلایدهای یک ارائه را با قالب مشخص به فایلی ذخیره می‌کند.
type: docs
weight: 404
url: /fa/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) متد

تمام اسلایدهای یک ارائه را به فایلی با قالب مشخص ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | مسیر فایل ایجاد شده. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | قالب داده‌های صادر شده. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) متد

تمام اسلایدهای یک ارائه را به یک جریان در قالب مشخص ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان خروجی. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | قالب داده‌های صادر شده. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) متد

تمام اسلایدهای یک ارائه را به فایلی با قالب مشخص و با گزینه‌های اضافی ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | مسیر فایل ایجاد شده. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | قالب داده‌های صادر شده. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | گزینه‌های قالب اضافی. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) متد

تمام اسلایدهای یک ارائه را به یک جریان در قالب مشخص و با گزینه‌های اضافی ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان خروجی. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | قالب داده‌های صادر شده. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | گزینه‌های قالب اضافی. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) متد

اسلایدهای مشخصی از یک ارائه را به فایلی با قالب مشخص ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | مسیر فایل ایجاد شده. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | آرایه‌ای از موقعیت اسلایدها، از ۱ شروع می‌شود. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | قالب داده‌های صادر شده. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) متد

اسلایدهای مشخصی از یک ارائه را به فایلی با قالب مشخص ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | مسیر فایل ایجاد شده. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | آرایه‌ای از موقعیت اسلایدها، از ۱ شروع می‌شود. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | قالب داده‌های صادر شده. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | گزینه‌های قالب اضافی. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) متد

اسلایدهای مشخصی از یک ارائه را به یک جریان در قالب مشخص ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان خروجی. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | آرایه‌ای از موقعیت اسلایدها، از ۱ شروع می‌شود. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | قالب داده‌های صادر شده. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) متد

اسلایدهای مشخصی از یک ارائه را به یک جریان در قالب مشخص ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان خروجی. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | آرایه‌ای از موقعیت اسلایدها، از ۱ شروع می‌شود. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | قالب داده‌های صادر شده. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | گزینه‌های قالب اضافی. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) متد

تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌های نشانگر XAML ذخیره می‌کند.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | گزینه‌های قالب XAML. |

## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## موارد مرتبط

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IPresentation](../)
* Class [Stream](../../../system.io/stream/)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)