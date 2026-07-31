---
title: CreateSignature()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat tanda tangan untuk data yang ditentukan.
type: docs
weight: 1
url: /id/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) metode

Membuat tanda tangan untuk data yang ditentukan.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) untuk menghitung hash. |

### Nilai Kembali

Tanda tangan yang dihitung dalam bentuk array byte.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) metode

Membuat tanda tangan untuk nilai hash yang ditentukan.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Algoritma hash yang digunakan saat membuat tanda tangan. |

### Nilai Kembali

Tanda tangan yang dihitung dalam bentuk array byte.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [AsymmetricSignatureFormatter](../)
* Kelas [HashAlgorithm](../../hashalgorithm/)
* Ruang nama [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)