---
title: X509Extension()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: المنشئ.
type: docs
weight: 1
url: /ar/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | البيانات المشفرة المرتبطة بالشهادة. |
| critical | **bool** | إشارة الحرجية. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) constructor

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | معرف [Object](../../../system/object/) المرتبط بالامتداد. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات الأولية المرتبطة بالشهادة. |
| critical | **bool** | إشارة الحرجية. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) constructor

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | معرف [Object](../../../system/object/) المرتبط بالامتداد. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات الأولية المرتبطة بالشهادة. |
| critical | **bool** | إشارة الحرجية. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* الفئة [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* الفئة [X509Extension](../)
* الفئة [Oid](../../../system.security.cryptography/oid/)
* الفئة [String](../../../system/string/)
* النطاق [System::Security::Cryptography::X509Certificates](../../)
* المكتبة [Aspose.Slides](../../../)