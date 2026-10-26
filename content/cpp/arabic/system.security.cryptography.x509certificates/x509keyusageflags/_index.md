---
title: X509KeyUsageFlags
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد كيفية استخدام مفتاح الشهادة.
type: docs
weight: 274
url: /ar/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags تعداد

يحدد كيف يمكن استخدام مفتاح الشهادة.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | لا توجد معلمات لاستخدام المفتاح. |
| EncipherOnly | 1 | يمكن استخدام المفتاح للتشفير فقط. |
| CrlSign | 2 | يمكن استخدام المفتاح لتوقيع قائمة إبطال الشهادة. |
| KeyCertSign | 4 | يمكن استخدام المفتاح لتوقيع الشهادات. |
| KeyAgreement | 8 | يمكن استخدام المفتاح لتحديد اتفاقية المفتاح. |
| DataEncipherment | 16 | يمكن استخدام المفتاح لتشفير البيانات. |
| KeyEncipherment | 32 | يمكن استخدام المفتاح لتشفير المفتاح. |
| NonRepudiation | 64 | يمكن استخدام المفتاح للمصادقة. |
| DigitalSignature | 128 | يمكن استخدام المفتاح كتوقيع رقمي. |
| DecipherOnly | 32768 | يمكن استخدام المفتاح فقط لفك التشفير. |

## انظر أيضًا

* نطاق [System::Security::Cryptography::X509Certificates](../)
* مكتبة [Aspose.Slides](../../)