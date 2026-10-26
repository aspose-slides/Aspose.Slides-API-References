---
title: CreateDecryptor()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek dekripsi dengan parameter eksplisit.
type: docs
weight: 14
url: /id/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metode


Membuat objek dekripsi dengan parameter eksplisit.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kunci enkripsi dalam bentuk array byte. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Nilai awal dalam bentuk array byte. |

### Nilai Kembali

Objek dekripsi yang baru dibuat.

## RC2Managed::CreateDecryptor() metode


Membuat objek dekripsi dengan parameter yang ditentukan oleh objek algoritma.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metode


Membuat objek dekripsi dengan parameter yang ditentukan oleh objek algoritma.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [ICryptoTransform](../../icryptotransform/)
* Kelas [RC2Managed](../)
* Namespace [System::Security::Cryptography](../../)
* Perpustakaan [Aspose.Slides](../../../)