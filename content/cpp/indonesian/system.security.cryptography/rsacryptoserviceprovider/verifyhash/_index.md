---
title: VerifyHash()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa tanda tangan data.
type: docs
weight: 222
url: /id/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) metode

Memeriksa tanda tangan data.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash yang dihitung untuk data yang diterima. |
| str | const [String](../../../system/string/)\& | Nama algoritma hash yang digunakan. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tanda tangan sebagaimana diterima. |

### Nilai Kembalian

True jika tanda tangan valid, false jika tidak.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) metode

Memverifikasi bahwa tanda tangan hash yang ditentukan valid.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Nilai hash dari data yang ditandatangani. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Data tanda tangan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Mode padding. Mengembalikan true jika tanda tangan valid, jika tidak - false. |

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [RSACryptoServiceProvider](../)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)