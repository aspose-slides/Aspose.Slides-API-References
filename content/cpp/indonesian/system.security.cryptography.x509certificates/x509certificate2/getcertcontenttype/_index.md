---
title: GetCertContentType()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan jenis sertifikat yang terdapat dalam byte array yang ditentukan.
type: docs
weight: 391
url: /id/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) metode

Mendapatkan jenis sertifikat yang terdapat dalam byte array yang ditentukan.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data sertifikat. |

### Nilai Kembali

Jenis sertifikat X.509.

## X509Certificate2::GetCertContentType(const String\&) metode

Mendapatkan jenis sertifikat yang terdapat dalam file yang ditentukan.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nama file sertifikat. |

### Nilai Kembali

Jenis sertifikat X.509.

## Lihat Juga

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Kelas [X509Certificate2](../)
* Kelas [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)