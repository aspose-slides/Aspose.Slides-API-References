---
title: CreateDecryptor()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek decryptor dengan parameter eksplisit.
type: docs
weight: 14
url: /id/system.security.cryptography/tripledesmanaged/createdecryptor/
---
## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metode


Membuat objek decryptor dengan parameter eksplisit.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kunci enkripsi dalam bentuk array byte. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Nilai awal dalam bentuk array byte. |

### Nilai Kembalian

Objek decryptor yang baru dibuat.

## TripleDESManaged::CreateDecryptor() metode


Membuat objek decryptor dengan parameter yang didefinisikan oleh objek algoritma.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metode


Membuat objek decryptor dengan parameter yang didefinisikan oleh objek algoritma.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [ICryptoTransform](../../icryptotransform/)
* Kelas [TripleDESManaged](../)
* Ruang Nama [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)