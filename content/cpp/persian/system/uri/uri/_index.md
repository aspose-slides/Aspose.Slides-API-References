---
title: Uri()
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء Uri می‌سازد که URI مشخص‌شده را نمایندگی می‌کند.
type: docs
weight: 287
url: /fa/system/uri/uri/
---
## Uri::Uri(const String\&) سازنده

یک شیء [Uri](../) می‌سازد که URI مشخص‌شده را نمایندگی می‌کند.

```cpp
System::Uri::Uri(const String &uriString)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | رشته URI که توسط شیء ساخته‌شده نمایندگی می‌شود |

## Uri::Uri(const String\&, bool) سازنده

یک شیء [Uri](../) می‌سازد که URI مشخص‌شده را نمایندگی می‌کند؛ یک آرگومان مشخص می‌کند که آیا URI باید Escape شود یا نه.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | رشته URI که توسط شیء ساخته‌شده نمایندگی می‌شود |
| dontEscape | **bool** | مشخص می‌کند که آیا URI نباید Escape شود |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) سازنده

یک شیء [Uri](../) از شیء [Uri](../) که URI پایه را نمایندگی می‌کند و نمایندگی رشته‌ای URI نسبی می‌سازد؛ یک آرگومان مشخص می‌کند که آیا URI باید Escape شود یا نه.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI پایه |
| relativeUri | const [String](../../string/)\& | URI نسبی که به URI پایه اضافه می‌شود |
| dontEscape | **bool** | مشخص می‌کند که آیا URI نباید Escape شود |

## Uri::Uri(const String\&, UriKind) سازنده

یک شیء [Uri](../) می‌سازد که URI مشخص‌شده را نمایندگی می‌کند؛ یک آرگومان نوع URI را مشخص می‌کند.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | رشته URI که توسط شیء ساخته‌شده نمایندگی می‌شود |
| uriKind | [UriKind](../../urikind/) | نوع URI را مشخص می‌کند |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) سازنده

یک شیء [Uri](../) از URI‌های پایه و نسبی مشخص‌شده می‌سازد.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI پایه |
| relativeUri | const [String](../../string/)\& | URI نسبی که به URI پایه اضافه می‌شود |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) سازنده

یک شیء [Uri](../) از URI‌های پایه و نسبی مشخص‌شده می‌سازد.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI پایه |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI نسبی که به URI پایه اضافه می‌شود |

## مراجع

* شمارشی [UriKind](../../urikind/)
* تعریف‌نوع [SharedPtr](../../sharedptr/)
* کلاس [String](../../string/)
* کلاس [Uri](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)