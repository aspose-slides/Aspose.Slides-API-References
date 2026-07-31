---
title: VerifyHash()
second_title: Referensi API Aspose.Slides untuk C++
description: Memverifikasi bahwa tanda tangan dari hash yang ditentukan valid.
type: docs
weight: 170
url: /id/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) metode

Memverifikasi bahwa tanda tangan untuk hash yang ditentukan valid.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Nilai hash dari data yang ditandatangani. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Data tanda tangan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Mode padding. mengembalikan true jika tanda tangan valid, jika tidak - false. |

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [RSASignaturePadding](../../rsasignaturepadding/)
* Kelas [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Ruang nama [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)