---
title: VerifySignature()
second_title: Referensi API Aspose.Slides untuk C++
description: Verifikasi tanda tangan DSA untuk data yang ditentukan.
type: docs
weight: 14
url: /id/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) metode

Verifikasi tanda tangan [DSA](../) untuk data yang ditentukan.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) ditandatangani dengan **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) tanda tangan. |

### Nilai Kembalian

true - jika **rgb_signature** cocok dengan tanda tangan [DSA](../) yang dihitung pada **rgb_hash**, jika tidak - false.

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Kelas [DSA](../)
* Ruang nama [System::Security::Cryptography](../../)
* Pustaka [Aspose.Slides](../../../)