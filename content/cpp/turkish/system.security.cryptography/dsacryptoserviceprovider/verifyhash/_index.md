---
title: VerifyHash()
second_title: Aspose.Slides için C++ API Referansı
description: Veri imzasını kontrol eder.
type: docs
weight: 222
url: /tr/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) metodu

Veri imzasını kontrol eder.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Alınan veriler için hesaplanan özet. |
| str | const [String](../../../system/string/)\& | Kullanılan özet algoritmasının adı. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Alındığı şekilde imza. |

### Dönüş Değeri

İmza geçerli ise true, aksi takdirde false.

## Başvurular

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [DSACryptoServiceProvider](../)
* Ad alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)