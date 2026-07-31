---
title: VerifyData()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa tanda tangan data.
type: docs
weight: 209
url: /id/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) method

Memeriksa tanda tangan data.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) untuk memeriksa tanda tangan. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algoritma hash yang akan digunakan. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tanda tangan sebagaimana diterima. |

### Nilai Kembali

Benar jika tanda tangan valid, salah jika tidak.

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Perpustakaan [Aspose.Slides](../../../)