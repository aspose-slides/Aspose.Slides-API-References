---
title: X509KeyUsageFlags
second_title: Aspose.Slides برای C++ مرجع API
description: نحوه استفاده از کلید گواهی را تعریف می‌کند.
type: docs
weight: 274
url: /fa/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum

Defines how the certificate key can be used.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| None | 0 | هیچ پارامتر استفاده از کلیدی وجود ندارد. |
| EncipherOnly | 1 | کلید فقط برای رمزنگاری قابل استفاده است. |
| CrlSign | 2 | کلید می‌تواند برای امضای فهرست ابطال گواهی استفاده شود. |
| KeyCertSign | 4 | کلید می‌تواند برای امضای گواهی‌ها استفاده شود. |
| KeyAgreement | 8 | کلید می‌تواند برای تعیین توافق کلید استفاده شود. |
| DataEncipherment | 16 | کلید می‌تواند برای رمزنگاری داده‌ها استفاده شود. |
| KeyEncipherment | 32 | کلید می‌تواند برای رمزنگاری کلید استفاده شود. |
| NonRepudiation | 64 | کلید می‌تواند برای احراز هویت استفاده شود. |
| DigitalSignature | 128 | کلید می‌تواند به عنوان امضای دیجیتال استفاده شود. |
| DecipherOnly | 32768 | کلید فقط برای رمزگشایی قابل استفاده است. |

## موارد مرتبط

* فضای نام [System::Security::Cryptography::X509Certificates](../)
* کتابخانه [Aspose.Slides](../../)