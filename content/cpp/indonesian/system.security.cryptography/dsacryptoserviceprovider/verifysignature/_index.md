---
title: VerifySignature()
second_title: Referensi API Aspose.Slides untuk C++
description: Verifikasi tanda tangan DSA untuk data yang ditentukan.
type: docs
weight: 118
url: /id/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) metode

Verifikasi tanda tangan [DSA](../../dsa/) untuk data yang ditentukan.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) ditandatangani dengan **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) tanda tangan. |

### Nilai Kembali

true - jika **rgb_signature** cocok dengan tanda tangan [DSA](../../dsa/) yang dihitung pada **rgb_hash**, sebaliknya - false.

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Kelas [DSACryptoServiceProvider](../)
* Ruang Nama [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)