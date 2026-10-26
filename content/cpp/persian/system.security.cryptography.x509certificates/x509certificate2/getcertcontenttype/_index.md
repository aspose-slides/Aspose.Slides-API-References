---
title: GetCertContentType()
second_title: Aspose.Slides برای C++ مرجع API
description: نوع گواهی‌نامه موجود در آرایه بایتی مشخص شده را برمی‌گرداند.
type: docs
weight: 391
url: /fa/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) متد

نوع گواهی‌نامه موجود در آرایه بایتی مشخص شده را برمی‌گرداند.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌های گواهی. |

### مقدار بازگشت

نوع گواهی‌نامه X.509.

## X509Certificate2::GetCertContentType(const String\&) متد

نوع گواهی‌نامه موجود در فایل مشخص شده را برمی‌گرداند.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | نام فایل گواهی. |

### مقدار بازگشت

نوع گواهی‌نامه X.509.

## موارد مرتبط

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* کلاس [X509Certificate2](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)