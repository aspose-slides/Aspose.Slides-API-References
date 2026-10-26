---
title: Presentation()
second_title: مرجع API Aspose.Slides للغة C++
description: يُنشئ هذا المنشئ عرضًا تقديميًا جديدًا من الصفر. العرض المخلق يحتوي على شريحة فارغة واحدة.
type: docs
weight: 417
url: /ar/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() منشئ

هذا المنشئ ينشئ عرض تقديمي جديد من الصفر. العرض المخلق يحتوي على شريحة فارغة واحدة.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) منشئ

هذا المنشئ ينشئ عرض تقديمي جديد من الصفر. العرض المخلق يحتوي على شريحة فارغة واحدة.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | خيارات التحميل الإضافية. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) منشئ

هذا المنشئ هو الآلية الأساسية لقراءة [Presentation](../) موجودة.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تدفق الإدخال. |
## ملاحظات

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) منشئ

هذا المنشئ هو الآلية الأساسية لقراءة [Presentation](../) موجودة.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تدفق الإدخال. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | خيارات التحميل الإضافية. |

## Presentation::Presentation(System::String) منشئ

هذا المنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه محتويات [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ملف الإدخال. |
## ملاحظات

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) منشئ

هذا المنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه محتويات [Presentation](../).

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ملف الإدخال. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | خيارات التحميل الإضافية. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../)
* Class [LoadOptions](../../loadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)