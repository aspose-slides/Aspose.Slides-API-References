---
title: X509KeyUsageExtension()
second_title: مرجع API Aspose.Slides برای C++
description: سازندهٔ پیش‌فرض.
type: docs
weight: 1
url: /fa/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() سازنده

سازندهٔ پیش‌فرض.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | داده‌های رمزگذاری شدهٔ استفاده‌های کلید. |
| critical | **bool** | علامت بحرانی. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | استفاده‌های کلید. |
| critical | **bool** | علامت بحرانی. |

## موارد مرتبط

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [X509KeyUsageExtension](../)
* کلاس [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* فضای نام [System::Security::Cryptography::X509Certificates](../../)
* کتابخانه [Aspose.Slides](../../../)