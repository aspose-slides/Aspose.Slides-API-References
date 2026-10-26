---
title: X509Extension()
second_title: Referensi API Aspose.Slides untuk C++
description: Konstruktor.
type: docs
weight: 1
url: /id/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Data yang dienkode terkait dengan sertifikat. |
| critical | **bool** | Tanda kritikalitas. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) pengidentifikasi terkait dengan ekstensi. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data mentah terkait dengan sertifikat. |
| critical | **bool** | Tanda kritikalitas. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) pengidentifikasi terkait dengan ekstensi. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data mentah terkait dengan sertifikat. |
| critical | **bool** | Tanda kritikalitas. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Kelas [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Kelas [X509Extension](../)
* Kelas [Oid](../../../system.security.cryptography/oid/)
* Kelas [String](../../../system/string/)
* Ruang Nama [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)