---
title: X509Extension()
second_title: Aspose.Slides برای C++ مرجع API
description: سازنده.
type: docs
weight: 1
url: /fa/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | داده‌های رمزنگاری‌شده مرتبط با گواهی‌نامه. |
| critical | **bool** | نشانهٔ بحرانی بودن. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) constructor

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) شناسه مرتبط با افزونه. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ خام مرتبط با گواهی‌نامه. |
| critical | **bool** | نشانهٔ بحرانی بودن. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) constructor

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) شناسه مرتبط با افزونه. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ خام مرتبط با گواهی‌نامه. |
| critical | **bool** | نشانهٔ بحرانی بودن. |

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* کلاس [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* کلاس [X509Extension](../)
* کلاس [Oid](../../../system.security.cryptography/oid/)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Security::Cryptography::X509Certificates](../../)
* کتابخانه [Aspose.Slides](../../../)