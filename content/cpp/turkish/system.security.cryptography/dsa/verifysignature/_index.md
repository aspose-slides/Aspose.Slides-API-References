---
title: VerifySignature()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen veri için DSA imzasını doğrulayın.
type: docs
weight: 14
url: /tr/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) metodu

Doğrula [DSA](../) imzasını belirtilen veri için.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) **rgb_signature** ile imzalanmış. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) imza. |

### Dönüş Değeri

true - eğer **rgb_signature** **rgb_hash** üzerinde hesaplanan [DSA](../) imzasıyla eşleşirse, aksi takdirde - false.

## İlgili

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Sınıf [DSA](../)
* AdAlanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)