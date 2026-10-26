---
title: SignHash()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghitung tanda tangan untuk nilai hash yang ditentukan.
type: docs
weight: 196
url: /id/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) method

Menghitung tanda tangan untuk nilai hash yang ditentukan.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Nilai hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritma hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Mode padding. mengembalikan [RSA](../../rsa/) tanda tangan untuk hash yang ditentukan. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) method

Menghitung tanda tangan dari nilai masukan yang ditentukan. Tidak diimplementasikan.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Nilai hash dari data yang akan ditandatangani. |
| str | const [String](../../../system/string/)\& | Pengidentifikasi algoritma hash yang digunakan untuk membuat hash. |

### Nilai Kembali

[RSA](../../rsa/) tanda tangan untuk data yang ditentukan.

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Class [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)