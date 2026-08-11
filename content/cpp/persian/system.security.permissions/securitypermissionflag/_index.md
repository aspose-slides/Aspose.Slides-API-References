---
title: SecurityPermissionFlag
second_title: مرجع API Aspose.Slides برای C++
description: پرچم‌های مجوز امنیتی.
type: docs
weight: 27
url: /fa/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum

پرچم‌های مجوز امنیتی.

```cpp
enum class SecurityPermissionFlag
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| NoFlags | 0 | بدون دسترسی. |
| Assertion | 1 | تأیید می‌کند که مجوز داده شده است. |
| UnmanagedCode | 2 | فراخوانی کد غیرمدیریت‌شده. |
| SkipVerification | 4 | دور زدن تأیید کد. |
| Execution | 8 | اجرای کد. |
| ControlThread | 16 | انجام عملیات روی رشته‌ها. |
| ControlEvidence | 32 | کنترل یا تغییر شواهد CLR. |
| ControlPolicy | 64 | مشاهده و تغییر سیاست. |
| SerializationFormatter | 128 | سریال‌سازی. |
| ControlDomainPolicy | 256 | تنظیم سیاست دامنه. |
| ControlPrincipal | 512 | کنترل شیء اصلی. |
| ControlAppDomain | 1024 | کنترل دامنه برنامه. |
| RemotingConfiguration | 2048 | پیکربندی ریموتینگ. |
| Infrastructure | 4096 | ادغام با زیرساخت CLR. |
| BindingRedirects | 8192 | انجام تغییر مسیر صریح بایندینگ. |
| AllFlags | 16383 | بدون محدودیت. |

## همچنین ببینید

* فضای‌نام [System::Security::Permissions](../)
* کتابخانه [Aspose.Slides](../../)