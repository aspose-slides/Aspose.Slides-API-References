---
title: GetNameInfo()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan nama subjek atau penerbit dari sertifikat.
type: docs
weight: 248
url: /id/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const metode

Mendapatkan nama subjek atau penerbit dari sertifikat.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Opsi pemformatan nama. |
| for_issuer | **bool** | Jika true, mengembalikan nama penerbit, jika tidak mengembalikan nama subjek. |

### Nilai Kembalian

Nama penerbit atau subjek yang diformat.

## Lihat Juga

* Enum [X509NameType](../../x509nametype/)
* Kelas [String](../../../system/string/)
* Kelas [X509Certificate2](../)
* Ruang Nama [System::Security::Cryptography::X509Certificates](../../)
* Perpustakaan [Aspose.Slides](../../../)