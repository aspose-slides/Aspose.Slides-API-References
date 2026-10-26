---
title: TryCreate()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كائن Uri يمثل URI المحدد; يحدد أحد المعاملات نوع URI.
type: docs
weight: 508
url: /ar/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) طريقة

إنشاء كائن [Uri](../) يمثل URI المحدد؛ يُحدد أحد المعاملات نوع URI.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | سلسلة URI التي سيمثلها الكائن المُنشأ |
| uriKind | [UriKind](../../urikind/) | يحدد نوع URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | معامل الإخراج الذي، إذا نجحت عملية الإنشاء، يشير إلى كائن [Uri](../) الجديد عند عودة الطريقة |

### قيمة الإرجاع

True إذا نجحت عملية الإنشاء، وإلا - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) طريقة

إنشاء كائن [Uri](../) من الكائن [Uri](../) المحدد الذي يمثل URI الأساسي وتمثيل السلسلة لـ URI النسبي.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI الأساسي |
| relativeUri | const [String](../../string/)\& | URI النسبي الذي يُضاف إلى URI الأساسي |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | معامل الإخراج الذي، إذا نجحت عملية الإنشاء، يشير إلى كائن [Uri](../) الجديد عند عودة الطريقة |

### قيمة الإرجاع

True إذا نجحت عملية الإنشاء، وإلا - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) طريقة

إنشاء كائن [Uri](../) من URI الأساسي والنسبي المحددين.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI الأساسي |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI النسبي الذي يُضاف إلى URI الأساسي |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | معامل الإخراج الذي، إذا نجحت عملية الإنشاء، يشير إلى كائن [Uri](../) الجديد عند عودة الطريقة |

### قيمة الإرجاع

True إذا نجحت عملية الإنشاء، وإلا - false

## See Also

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)