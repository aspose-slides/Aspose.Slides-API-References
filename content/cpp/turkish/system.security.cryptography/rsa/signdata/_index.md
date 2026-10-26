---
title: SignData()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen veri dizisinin hash değerini belirtilen hash algoritması ve doldurma (padding) kullanarak hesaplar ve sonucu imzalar.
type: docs
weight: 131
url: /tr/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metodu

Belirtilen veri dizisinin hash değerini belirtilen hash algoritması ve doldurma (padding) kullanarak hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Giriş veri dizisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Doldurma modu. Giriş verisi için [RSA](../) imzasını döndürür. |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metodu

Belirtilen veri dizisinin hash değerini belirtilen hash algoritması ve doldurma (padding) kullanarak hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Giriş veri dizisi. |
| offset | **int32_t** | **data** içindeki ofset. |
| count | **int32_t** | Giriş verisi olarak kullanılacak byte sayısı. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Doldurma modu. Giriş verisi için [RSA](../) imzasını döndürür. |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metodu

Belirtilen ikili akışın hash değerini belirtilen hash algoritması ve doldurma (padding) kullanarak hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | İkili akış. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Doldurma modu. Giriş verisi için [RSA](../) imzasını döndürür. |

## Ayrıca Bakınız

* Tip Tanımı [ByteArrayPtr](../../../system/bytearrayptr/)
* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Tip Tanımı [StreamPtr](../../../system/streamptr/)
* Sınıf [RSASignaturePadding](../../rsasignaturepadding/)
* Sınıf [RSA](../)
* Yapı [HashAlgorithmName](../../hashalgorithmname/)
* İsim Alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)