---
title: Create()
second_title: مرجع API Aspose.Slides برای C++
description: یک پیاده‌سازی پیش‌فرض الگوریتم ECDSA ایجاد می‌کند.
type: docs
weight: 131
url: /fa/system.security.cryptography/ecdsa/create/
---
## روش ECDsa::Create() method

یک پیاده‌سازی پیش‌فرض الگوریتم ECDSA ایجاد می‌کند.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### مقدار بازگشت

شیء الگوریتم ECDSA.

## روش ECDsa::Create(const ECCurve\&) method

یک پیاده‌سازی پیش‌فرض الگوریتم ECDSA را با کلید تازه ساخته شده بر روی منحنی مشخص شده ایجاد می‌کند.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | منحنی مورد استفاده برای ایجاد کلید. |

### مقدار بازگشت

شیء الگوریتم ECDSA.

## روش ECDsa::Create(const ECParameters\&) method

یک پیاده‌سازی پیش‌فرض الگوریتم ECDSA با استفاده از پارامترهای مشخص شده ایجاد می‌کند.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | پارامترهایی که کلید را نمایند. |

### مقدار بازگشت

شیء الگوریتم ECDSA.

## روش ECDsa::Create(const String\&) method

یک پیاده‌سازی مشخص الگوریتم ECDSA ایجاد می‌کند.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | نام الگوریتم. |

### مقدار بازگشت

شیء الگوریتم ECDSA.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ECDsa](../)
* کلاس [String](../../../system/string/)
* ساختار [ECCurve](../../eccurve/)
* ساختار [ECParameters](../../ecparameters/)
* فضای‌نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)