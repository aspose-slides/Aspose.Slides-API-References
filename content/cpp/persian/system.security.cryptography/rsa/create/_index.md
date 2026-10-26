---
title: Create()
second_title: مرجع API Aspose.Slides برای C++
description: پیاده‌سازی پیش‌فرض الگوریتم RSA را ایجاد می‌کند.
type: docs
weight: 183
url: /fa/system.security.cryptography/rsa/create/
---
## RSA::Create() متد

یک پیاده‌سازی پیش‌فرض از الگوریتم [RSA](../) ایجاد می‌کند.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) متد

یک پیاده‌سازی پیش‌فرض از الگوریتم [RSA](../) ایجاد می‌کند.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | باید \"System.Security.Cryptography.RSACryptoServiceProvider\" باشد. |

## RSA::Create(int32_t) متد

یک پیاده‌سازی پیش‌فرض از الگوریتم [RSA](../) با اندازه کلید مشخص ایجاد می‌کند.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | اندازه کلید، بر حسب بیت. |

## RSA::Create(const RSAParameters\&) متد

یک پیاده‌سازی پیش‌فرض از الگوریتم [RSA](../) با پارامترهای مشخص ایجاد می‌کند.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | پارامترهای الگوریتم [RSA](../). |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSA](../)
* Class [String](../../../system/string/)
* Struct [RSAParameters](../../rsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)