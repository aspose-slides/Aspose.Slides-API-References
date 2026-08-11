---
title: Uri()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كائن Uri يمثل URI المحدد.
type: docs
weight: 287
url: /ar/system/uri/uri/
---
## Uri::Uri(const String\&) منشئ

يقوم بإنشاء كائن [Uri](../) يمثل URI المحدد.

```cpp
System::Uri::Uri(const String &uriString)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | سلسلة URI التي سيتم تمثيلها بواسطة الكائن الجاري إنشاؤه |

## Uri::Uri(const String\&, bool) منشئ

يقوم بإنشاء كائن [Uri](../) يمثل URI المحدد؛ يحدد وسيط ما إذا كان يجب عدم هروب URI.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | سلسلة URI التي سيتم تمثيلها بواسطة الكائن الجاري إنشاؤه |
| dontEscape | **bool** | يحدد ما إذا كان يجب عدم هروب URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) منشئ

يقوم بإنشاء كائن [Uri](../) من الكائن [Uri](../) المحدد الذي يمثل URI الأساسي وتمثيل السلسلة لـ URI النسبي؛ يحدد وسيط ما إذا كان يجب هروب URI.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI الأساسي |
| relativeUri | const [String](../../string/)\& | URI النسبي الذي يُضاف إلى URI الأساسي |
| dontEscape | **bool** | يحدد ما إذا كان يجب عدم هروب URI |

## Uri::Uri(const String\&, UriKind) منشئ

يقوم بإنشاء كائن [Uri](../) يمثل URI المحدد؛ يحدد وسيط نوع URI.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | سلسلة URI التي سيتم تمثيلها بواسطة الكائن الجاري إنشاؤه |
| uriKind | [UriKind](../../urikind/) | يحدد نوع URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) منشئ

يقوم بإنشاء كائن [Uri](../) من URIs الأساسي والنسبي المحددين.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI الأساسي |
| relativeUri | const [String](../../string/)\& | URI النسبي الذي يُضاف إلى URI الأساسي |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) منشئ

يقوم بإنشاء كائن [Uri](../) من URIs الأساسي والنسبي المحددين.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI الأساسي |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI النسبي الذي يُضاف إلى URI الأساسي |

## انظر أيضًا

* تعداد [UriKind](../../urikind/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [Uri](../)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)