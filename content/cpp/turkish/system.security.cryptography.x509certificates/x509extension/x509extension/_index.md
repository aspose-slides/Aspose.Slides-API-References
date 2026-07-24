---
title: X509Extension()
second_title: Aspose.Slides C++ için API Referansı
description: Yapıcı.
type: docs
weight: 1
url: /tr/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) Yapıcı

Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Sertifika ile ilişkili kodlanmış veri. |
| critical | **bool** | Kritiklik işareti. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) Yapıcı

Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) uzantıyla ilişkili tanımlayıcı. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sertifika ile ilişkili ham veri. |
| critical | **bool** | Kritiklik işareti. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) Yapıcı

Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) uzantıyla ilişkili tanımlayıcı. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sertifika ile ilişkili ham veri. |
| critical | **bool** | Kritiklik işareti. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Sınıf [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Sınıf [X509Extension](../)
* Sınıf [Oid](../../../system.security.cryptography/oid/)
* Sınıf [String](../../../system/string/)
* AdAlanı [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)