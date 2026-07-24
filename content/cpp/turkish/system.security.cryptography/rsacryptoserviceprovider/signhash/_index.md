---
title: SignHash()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen hash değeri için imzayı hesaplar.
type: docs
weight: 196
url: /tr/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) metodu


Belirtilen hash değeri için imzayı hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash değeri. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash algoritması. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Dolgu modu. belirtilen hash için [RSA](../../rsa/) imzasını döndürür. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) metodu


Belirtilen girdi değerinin imzasını hesaplar. Uygulanmadı.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmzalanacak verinin hash değeri. |
| str | const [String](../../../system/string/)\& | Hash'i oluşturmak için kullanılan hash algoritması tanımlayıcısı. |

### Dönüş Değeri

[RSA](../../rsa/) imzası belirtilen veri için.

## İlgili

* Tip Tanımı [ByteArrayPtr](../../../system/bytearrayptr/)
* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [RSASignaturePadding](../../rsasignaturepadding/)
* Sınıf [RSACryptoServiceProvider](../)
* Sınıf [String](../../../system/string/)
* Yapı [HashAlgorithmName](../../hashalgorithmname/)
* Ad Alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)