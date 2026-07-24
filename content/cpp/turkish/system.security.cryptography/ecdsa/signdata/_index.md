---
title: SignData()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen veri dizisinin hash değerini belirtilen hash algoritması kullanarak hesaplar ve sonucu imzalar.
type: docs
weight: 79
url: /tr/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method

Verilen veri dizisinin belirtilen hash algoritması kullanılarak hash değerini hesaplar ve sonucu imzalar.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Giriş veri dizisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. Giriş verisi için ECDSA imzasını döndürür. |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method

Verilen veri dizisinin belirtilen hash algoritması kullanılarak hash değerini hesaplar ve sonucu imzalar.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Giriş veri dizisi. |
| offset | **int32_t** | **data** içinde ofset. |
| count | **int32_t** | Giriş verisi olarak kullanılacak bayt sayısı. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. Giriş verisi için ECDSA imzasını döndürür. |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) method

Belirtilen ikili akışın hash değerini belirtilen hash algoritması kullanarak hesaplar ve sonucu imzalar.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | İkili akış. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. Giriş verisi için ECDSA imzasını döndürür. |

## İlgili

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Sınıf [ECDsa](../)
* Yapı [HashAlgorithmName](../../hashalgorithmname/)
* İsim Alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)