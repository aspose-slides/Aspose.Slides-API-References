---
title: Add()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف مصفوفة بايت إلى مخزن XmlPreloadedResolver ويربطها بـ URI. إذا كان المخزن يحتوي بالفعل على ربط لنفس URI، يتم استبدال الربط الحالي.
type: docs
weight: 79
url: /ar/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) طريقة

يضيف مصفوفة بايت إلى مخزن [XmlPreloadedResolver](../) ويربطها بـ URI. إذا كان المخزن يحتوي بالفعل على ربط لنفس الـ URI، يتم استبدال الربط الحالي.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI للبيانات التي يتم إضافتها إلى مخزن [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة بايت تحتوي على البيانات التي تتطابق مع الـ URI المقدم. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

يضيف مصفوفة بايت إلى مخزن [XmlPreloadedResolver](../) ويربطها بـ URI. إذا كان المخزن يحتوي بالفعل على ربط لنفس الـ URI، يتم استبدال الربط الحالي.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI للبيانات التي يتم إضافتها إلى مخزن [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة بايت تحتوي على البيانات التي تتطابق مع الـ URI المقدم. |
| offset | **int32_t** | الإزاحة في مصفوفة البايت المقدمة حيث تبدأ البيانات. |
| count | **int32_t** | عدد البايتات التي يجب قراءتها من مصفوفة البايت، بدءًا من الإزاحة المقدمة. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) طريقة

يضيف Stream إلى مخزن [XmlPreloadedResolver](../) ويربطه بـ URI. إذا كان المخزن يحتوي بالفعل على ربط لنفس الـ URI، يتم استبدال الربط الحالي.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI للبيانات التي يتم إضافتها إلى مخزن [XmlPreloadedResolver](../). |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream يحتوي على البيانات التي تتطابق مع الـ URI المقدم. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) طريقة

يضيف سلسلة من البيانات المحملة مسبقًا إلى مخزن [XmlPreloadedResolver](../) ويربطها بـ URI. إذا كان المخزن يحتوي بالفعل على ربط لنفس الـ URI، يتم استبدال الربط الحالي.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI للبيانات التي يتم إضافتها إلى مخزن [XmlPreloadedResolver](../). |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) يحتوي على البيانات التي تتطابق مع الـ URI المقدم. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)