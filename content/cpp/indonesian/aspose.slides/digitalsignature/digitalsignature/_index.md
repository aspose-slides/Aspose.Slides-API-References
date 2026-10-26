---
title: DigitalSignature()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat objek DigitalSignature baru dengan sertifikat yang ditentukan.
type: docs
weight: 66
url: /id/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) konstruktor

Membuat objek [DigitalSignature](../) baru dengan sertifikat yang ditentukan.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Sertifikat yang akan digunakan untuk menandatangani presentasi. |

## DigitalSignature::DigitalSignature(System::String, System::String) konstruktor

Membuat objek [DigitalSignature](../) baru dengan jalur file sertifikat dan kata sandi yang ditentukan.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Jalur ke file dengan sertifikat. |
| password | [System::String](../../../system/string/) | Kata sandi yang diperlukan untuk mengakses sertifikat. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Kelas [DigitalSignature](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)