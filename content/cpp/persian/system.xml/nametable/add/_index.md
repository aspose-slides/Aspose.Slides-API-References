---
title: Add()
second_title: Aspose.Slides برای C++ مرجع API
description: رشتهٔ مشخص‌شده را اتم‌سازی می‌کند و به NameTable اضافه می‌نماید.
type: docs
weight: 14
url: /fa/system.xml/nametable/add/
---
## NameTable::Add(const String\&) متد

رشتهٔ مشخص‌شده را اتم‌سازی می‌کند و به [NameTable](../) اضافه می‌کند.

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | رشته‌ای که باید اضافه شود. |

### مقدار برگشتی

رشتهٔ اتم‌سازی‌شده یا رشتهٔ موجود اگر قبلاً در [NameTable](../) وجود داشته باشد.

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) متد

رشتهٔ مشخص‌شده را اتم‌سازی می‌کند و به [NameTable](../) اضافه می‌کند.

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | آرایهٔ کاراکتری که حاوی رشتهٔ مورد اضافه شدن است. |
| start | **int32_t** | اندیس مبتنی بر صفر در آرایه که اولین کاراکتر رشته را مشخص می‌کند. |
| len | **int32_t** | تعداد کاراکترهای رشته. |

### مقدار برگشتی

رشتهٔ اتم‌سازی‌شده یا رشتهٔ موجود اگر در [NameTable](../) پیش از این موجود باشد. اگر **len** صفر باشد، [String::Empty](../../../system/string/empty/) بازگردانده می‌شود.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [NameTable](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)