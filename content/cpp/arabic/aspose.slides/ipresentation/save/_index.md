---
title: Save()
second_title: مرجع API Aspose.Slides للغة C++
description: يحفظ جميع شرائح العرض التقديمي في ملف بالتنسيق المحدد.
type: docs
weight: 404
url: /ar/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) method


يحفظ جميع شرائح العرض التقديمي في ملف بالتنسيق المحدد.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | المسار إلى الملف الذي تم إنشاؤه. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | تنسيق البيانات المصدرة. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) method


يحفظ جميع شرائح العرض التقديمي في دفق بالتنسيق المحدد.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإخراج. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | تنسيق البيانات المصدرة. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


يحفظ جميع شرائح العرض التقديمي في ملف بالتنسيق المحدد ومع خيارات إضافية.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | المسار إلى الملف الذي تم إنشاؤه. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | تنسيق البيانات المصدرة. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | خيارات تنسيق إضافية. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


يحفظ جميع شرائح العرض التقديمي في دفق بالتنسيق المحدد ومع خيارات إضافية.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإخراج. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | تنسيق البيانات المصدرة. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | خيارات تنسيق إضافية. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method


يحفظ الشرائح المحددة من العرض التقديمي في ملف بالتنسيق المحدد.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | المسار إلى الملف الذي تم إنشاؤه. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | تنسيق البيانات المصدرة. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


يحفظ الشرائح المحددة من العرض التقديمي في ملف بالتنسيق المحدد.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | المسار إلى الملف الذي تم إنشاؤه. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | تنسيق البيانات المصدرة. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | خيارات تنسيق إضافية. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method


يحفظ الشرائح المحددة من العرض التقديمي في دفق بالتنسيق المحدد.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإخراج. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | تنسيق البيانات المصدرة. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method


يحفظ الشرائح المحددة من العرض التقديمي في دفق بالتنسيق المحدد.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإخراج. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | تنسيق البيانات المصدرة. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | خيارات تنسيق إضافية. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) method


يحفظ جميع شرائح العرض التقديمي في مجموعة من الملفات التي تمثل ترميز XAML.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | خيارات تنسيق XAML. |
## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## انظر أيضا

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