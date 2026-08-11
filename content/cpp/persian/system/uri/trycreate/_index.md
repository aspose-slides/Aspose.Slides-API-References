---
title: TryCreate()
second_title: مرجع API Aspose.Slides برای C++
description: یک شی Uri می‌سازد که URI مشخص‌شده را نشان می‌دهد؛ یک آرگومان نوع URI را مشخص می‌کند.
type: docs
weight: 508
url: /fa/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) متد

یک شی [Uri](../) می‌سازد که URI مشخص‌شده را نشان می‌دهد؛ یک آرگومان نوع URI را مشخص می‌کند.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | رشته URI که باید توسط شی ساخته‌شده نشان داده شود |
| uriKind | [UriKind](../../urikind/) | نوع URI را مشخص می‌کند |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | آرگومان خروجی که در صورت موفقیت ساخت، به شی [Uri](../) تازه‌ساخته در هنگام بازگشت متد اشاره می‌کند |

### مقدار بازگشت

True if the construction succeeded, otherwise - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) متد

یک شی [Uri](../) را از شی [Uri](../) مشخص‌شده که URI پایه را نشان می‌دهد و نمایش رشته‌ای URI نسبی می‌سازد.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI پایه |
| relativeUri | const [String](../../string/)\& | URI نسبی که به URI پایه اضافه می‌شود |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | آرگومان خروجی که در صورت موفقیت ساخت، به شی [Uri](../) تازه‌ساخته در هنگام بازگشت متد اشاره می‌کند |

### مقدار بازگشت

True if the construction succeeded, otherwise - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) متد

یک شی [Uri](../) را از URIهای پایه و نسبی مشخص‌شده می‌سازد.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI پایه |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI نسبی که به URI پایه اضافه می‌شود |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | آرگومان خروجی که در صورت موفقیت ساخت، به شی [Uri](../) تازه‌ساخته در هنگام بازگشت متد اشاره می‌کند |

### مقدار بازگشت

True if the construction succeeded, otherwise - false

## موارد مرتبط

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)