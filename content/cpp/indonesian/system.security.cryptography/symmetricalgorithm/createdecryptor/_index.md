---
title: CreateDecryptor()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat decryptor dengan parameter yang terkait dengan objek algoritma.
type: docs
weight: 196
url: /id/system.security.cryptography/symmetricalgalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() metode


Membuat decryptor dengan parameter yang terkait dengan objek algoritma.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```


### Nilai Kembali

Objek decryptor yang baru dibuat.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metode


Membuat decryptor dengan parameter eksplisit.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kunci yang akan digunakan. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Nilai awal yang akan digunakan. |

### Nilai Kembali

Objek decryptor yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [ICryptoTransform](../../icryptotransform/)
* Kelas [SymmetricAlgorithm](../)
* Ruang Nama [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)