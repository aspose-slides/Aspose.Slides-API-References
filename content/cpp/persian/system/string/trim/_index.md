---
title: Trim()
second_title: Aspose.Slides برای C++ مرجع API
description: تمام کاراکترهای فضای خالی را از ابتدا و انتهای رشته حذف می‌کند.
type: docs
weight: 677
url: /fa/system/string/trim/
---
## String::Trim() const متد

تمام کاراکترهای فاصله را از ابتدا و انتهای رشته حذف می‌کند.

```cpp
String System::String::Trim() const
```

### مقدار بازگشتی

[String](../) بدون فاصله در ابتدا یا انتها.

## String::Trim(char_t) const متد

تمام تکرارهای کاراکتر ورودی را از ابتدا و انتهای رشته حذف می‌کند.

```cpp
String System::String::Trim(char_t ch) const
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char_t | نماد برای حذف. |

### مقدار بازگشتی

نتیجه حذف.

## String::Trim(const String\&) const متد

تمام تکرارهای کاراکترهای ورودی را از ابتدا و انتهای رشته حذف می‌کند.

```cpp
String System::String::Trim(const String &anyOf) const
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) از کاراکترهای برای حذف. |

### مقدار بازگشتی

[String](../) بدون کاراکترهای حذف شده.

## String::Trim(const ArrayPtr\<char_t\>\&) const متد

تمام تکرارهای کاراکترهای ورودی را از ابتدا و انتهای رشته حذف می‌کند.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) از کاراکترهای برای حذف. |

### مقدار بازگشتی

[String](../) بدون کاراکترهای حذف شده.

## مراجع

* Typedef [ArrayPtr](../../arrayptr/)
* کلاس [String](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)