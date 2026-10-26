---
title: X509KeyStorageFlags
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد كيفية تخزين المفتاح.
type: docs
weight: 261
url: /ar/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags تعداد

يحدد كيفية تخزين المفتاح.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| DefaultKeySet | 0 | استخدم مجموعة المفاتيح الافتراضية. |
| UserKeySet | 1 | استخدم المخزن المرتبط بالمستخدم بدلاً من المخزن المحلي للجهاز. |
| MachineKeySet | 2 | استخدم مخزن الجهاز المحلي بدلاً من مخزن المستخدم. |
| Exportable | 4 | يُعْلِن المفاتيح المستوردة على أنها قابلة للتصدير. |
| UserProtected | 8 | إخطار المستخدم بأن المفتاح قيد الاستخدام. |
| PersistKeySet | 16 | يتم حفظ المفتاح عند استيراد الشهادة. |

## انظر أيضًا

* نطاق [System::Security::Cryptography::X509Certificates](../)
* مكتبة [Aspose.Slides](../../)