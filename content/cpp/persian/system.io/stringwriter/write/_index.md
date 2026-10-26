---
title: Write()
second_title: مرجع API Aspose.Slides برای C++
description: کاراکتر مشخص‌شده را در جریان می‌نویسد.
type: docs
weight: 40
url: /fa/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) متد

کاراکتر مشخص‌شده را در جریان می‌نویسد.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | مقداری که باید نوشته شود |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) متد

بخش مشخص‌شده‌ای از کاراکترها را از آرایه کاراکتر مشخص‌شده به جریان می‌نویسد.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | آرایه‌ای که کاراکترهای برای نوشتن را شامل می‌شود |
| index | **int32_t** | یک اندیس صفر-پایه از عنصر در **buffer** که زیرمحدوده‌ی نوشتن از آن شروع می‌شود |
| count | **int32_t** | تعداد کاراکترهای موجود در زیرمحدوده‌ی قابل نوشتن |

## StringWriter::Write(const String\&) متد

رشته‌ای که باید نوشته شود را به جریان می‌نویسد.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | رشته‌ای برای نوشتن |

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [StringWriter](../)
* کلاس [String](../../../system/string/)
* فضای نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)