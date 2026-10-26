---
title: VerifyHash()
second_title: Aspose.Slides için C++ API Referansı
description: Veri imzasını kontrol eder.
type: docs
weight: 222
url: /tr/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) metot

Veri imzasını kontrol eder.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Alınan veri için hesaplanan hash. |
| str | const [String](../../../system/string/)\& | Kullanılan hash algoritmasının adı. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Alınan imza. |

### Dönüş Değeri

İmza geçerli ise true, aksi takdirde false.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) metot

Belirtilen hash'in imzasının geçerli olduğunu doğrular.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | İmzalı verinin hash değeri. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | İmza verisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Doldurma modu. İmza geçerli ise true döndür, aksi takdirde false. |

## Ayrıca Bakınız

* TipTanımı [ByteArrayPtr](../../../system/bytearrayptr/)
* TipTanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [RSACryptoServiceProvider](../)
* Sınıf [RSASignaturePadding](../../rsasignaturepadding/)
* Yapı [HashAlgorithmName](../../hashalgorithmname/)
* İsimAlanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)