---
title: VerifyHash()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen hash'in imzasının geçerli olduğunu doğrular.
type: docs
weight: 170
url: /tr/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) metot

Belirtilen hash'in imzasının geçerli olduğunu doğrular.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | İmzalanmış verinin hash değeri. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | İmza verisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Dolgu modu. imza geçerli ise true döner, aksi takdirde false. |

## İlgili

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [RSASignaturePadding](../../rsasignaturepadding/)
* Sınıf [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Ad alanı [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)