---
title: Create()
second_title: مرجع API Aspose.Slides برای C++
description: پیاده‌سازی پیش‌فرض الگوریتم DSA را ایجاد می‌کند.
type: docs
weight: 105
url: /fa/system.security.cryptography/dsa/create/
---
## DSA::Create() متد

[DSA](../) پیاده‌سازی پیش‌فرض الگوریتم را ایجاد می‌کند.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### مقدار بازگشت

[DSA](../) شی الگوریتم.

## DSA::Create(const String\&) متد

[DSA](../) پیاده‌سازی پیش‌فرض الگوریتم را ایجاد می‌کند.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | باید "System.Security.Cryptography.DSACryptoServiceProvider" باشد. |

### مقدار بازگشت

[DSA](../) شی الگوریتم.

## DSA::Create(int32_t) متد

[DSA](../) پیاده‌سازی پیش‌فرض الگوریتم را با اندازه کلید مشخص ایجاد می‌کند.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | اندازه کلید، بر حسب بیت. |

## DSA::Create(const DSAParameters\&) متد

[DSA](../) پیاده‌سازی پیش‌فرض الگوریتم را با پارامترهای مشخص ایجاد می‌کند.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | پارامترهای الگوریتم [DSA](../). |

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [DSA](../)
* کلاس [String](../../../system/string/)
* ساختار [DSAParameters](../../dsaparameters/)
* فضای-نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)