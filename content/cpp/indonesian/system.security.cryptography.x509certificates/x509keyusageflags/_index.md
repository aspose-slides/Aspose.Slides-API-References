---
title: X509KeyUsageFlags
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan bagaimana kunci sertifikat dapat digunakan.
type: docs
weight: 274
url: /id/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum

Mendefinisikan bagaimana kunci sertifikat dapat digunakan.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | 0 | Tidak ada parameter penggunaan kunci. |
| EncipherOnly | 1 | Kunci hanya dapat digunakan untuk enkripsi. |
| CrlSign | 2 | Kunci dapat digunakan untuk menandatangani daftar pencabutan sertifikat. |
| KeyCertSign | 4 | Kunci dapat digunakan untuk menandatangani sertifikat. |
| KeyAgreement | 8 | Kunci dapat digunakan untuk menentukan kesepakatan kunci. |
| DataEncipherment | 16 | Kunci dapat digunakan untuk enkripsi data. |
| KeyEncipherment | 32 | Kunci dapat digunakan untuk enkripsi kunci. |
| NonRepudiation | 64 | Kunci dapat digunakan untuk otentikasi. |
| DigitalSignature | 128 | Kunci dapat digunakan sebagai tanda tangan digital. |
| DecipherOnly | 32768 | Kunci hanya dapat digunakan untuk dekripsi. |

## Lihat Juga

* Ruang Nama [System::Security::Cryptography::X509Certificates](../)
* Perpustakaan [Aspose.Slides](../../)