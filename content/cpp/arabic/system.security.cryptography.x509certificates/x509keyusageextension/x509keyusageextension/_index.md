---
title: X509KeyUsageExtension()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: منشئ افتراضي.
type: docs
weight: 1
url: /ar/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() منشئ

منشئ افتراضي.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) منشئ

منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | البيانات المشفرة لاستخدامات المفتاح. |
| critical | **bool** | علامة الحرجية. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) منشئ

منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | استخدامات المفتاح. |
| critical | **bool** | علامة الحرجية. |

## انظر أيضًا

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [X509KeyUsageExtension](../)
* فئة [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* نطاق [System::Security::Cryptography::X509Certificates](../../)
* مكتبة [Aspose.Slides](../../../)