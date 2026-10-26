---
title: VerifyHash()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa tanda tangan data.
type: docs
weight: 222
url: /id/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) metode

Memeriksa tanda tangan data.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash yang dihitung untuk data yang diterima. |
| str | const [String](../../../system/string/)\& | Nama algoritma hash yang digunakan. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tanda tangan sebagaimana diterima. |

### Nilai Kembali

True jika tanda tangan valid, false jika tidak.

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [DSACryptoServiceProvider](../)
* Ruang Nama [System::Security::Cryptography](../../)
* Perpustakaan [Aspose.Slides](../../../)