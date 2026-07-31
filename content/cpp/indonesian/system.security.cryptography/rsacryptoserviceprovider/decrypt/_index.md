---
title: Decrypt()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendekripsi pesan. Tidak diimplementasikan.
type: docs
weight: 105
url: /id/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) metode


Mendekripsi pesan. Tidak diimplementasikan.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) untuk mendekripsi. |
| use_oaep | **bool** | True untuk menggunakan OAEP padding, false untuk menggunakan PKCS#1 v1.5 padding. |

### Nilai Kembalian

Decrypted data array.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) metode


Mendekripsi data masukan menggunakan mode padding yang ditentukan.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) array untuk mendekripsi. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | Mode padding. |

### Nilai Kembalian

Decrypted data in byte array format.

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [RSACryptoServiceProvider](../)
* Kelas [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Ruang Nama [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)