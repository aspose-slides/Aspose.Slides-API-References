---
title: Export()
second_title: مرجع API Aspose.Slides برای C++
description: شیء فعلی را با استفاده از قالب مشخص به یک آرایه بایت صادر می‌کند. پیاده‌سازی نشده.
type: docs
weight: 287
url: /fa/system.security.cryptography.x509certificates/x509certificate/export/
---
## X509Certificate::Export(X509ContentType) const متد

شیء فعلی را با استفاده از قالب مشخص به یک آرایه بایت صادر می‌کند. پیاده‌سازی نشده.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | مشخص می‌کند که داده‌های خروجی چگونه قالب‌بندی شوند. |

### مقدار بازگشت

یک آرایه بایت که شیء فعلی را نشان می‌دهد.

## X509Certificate::Export(X509ContentType, const SecureStringPtr\&) const متد

شیء فعلی را با استفاده از قالب مشخص به یک آرایه بایت صادر می‌کند. پیاده‌سازی نشده.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const SecureStringPtr &password) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | مشخص می‌کند که داده‌های خروجی چگونه قالب‌بندی شوند. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | رمز عبوری که برای دسترسی به داده‌های گواهی‌نامه لازم است. |

### مقدار بازگشت

یک آرایه بایت که شیء فعلی را نشان می‌دهد.

## X509Certificate::Export(X509ContentType, const String\&) const متد

شیء فعلی را با استفاده از قالب مشخص به یک آرایه بایت صادر می‌کند. پیاده‌سازی نشده.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const String &password) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | مشخص می‌کند که داده‌های خروجی چگونه قالب‌بندی شوند. |
| password | const [String](../../../system/string/)\& | رمز عبوری که برای دسترسی به داده‌های گواهی‌نامه لازم است. |

### مقدار بازگشت

یک آرایه بایت که شیء فعلی را نشان می‌دهد.

## موارد مرتبط

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)