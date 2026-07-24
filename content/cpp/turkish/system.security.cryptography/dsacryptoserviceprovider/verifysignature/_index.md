---
title: VerifySignature()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen veri için DSA imzasını doğrula.
type: docs
weight: 118
url: /tr/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) metot


Belirtilen veri için [DSA](../../dsa/) imzasını doğrula.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) **rgb_signature** ile imzalanmış. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) imzası. |

### Dönüş Değeri

true - eğer **rgb_signature** **rgb_hash** üzerinde hesaplanan [DSA](../../dsa/) imzasıyla eşleşiyorsa, aksi takdirde - false.

## İlgili

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Sınıf [DSACryptoServiceProvider](../)
* AdAlanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)