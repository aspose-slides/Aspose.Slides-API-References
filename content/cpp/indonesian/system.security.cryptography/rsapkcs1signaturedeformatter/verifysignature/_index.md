---
title: VerifySignature()
second_title: Referensi API Aspose.Slides untuk C++
description: Memverifikasi tanda tangan hash data.
type: docs
weight: 40
url: /id/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metode

Memverifikasi tanda tangan dari hash data.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hash yang dihitung untuk data. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tanda tangan yang diterima untuk data. |

### Nilai Kembalian

True jika tanda tangan valid, false jika tidak.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [RSAPKCS1SignatureDeformatter](../)
* Ruang Nama [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)