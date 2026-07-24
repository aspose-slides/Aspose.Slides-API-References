---
title: SignData()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen veri dizisinin hash değerini belirtilen hash algoritmasıyla hesaplar ve sonucu imzalar.
type: docs
weight: 79
url: /tr/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) yöntemi

Belirtilen veri dizisinin hash değerini belirtilen hash algoritmasıyla hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Giriş veri dizisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Karma algoritması. Giriş veri için [DSA](../) imzasını döndürür. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) yöntemi

Belirtilen veri dizisinin hash değerini belirtilen hash algoritmasıyla hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Giriş veri dizisi. |
| offset | **int32_t** | **data** içinde ofset. |
| count | **int32_t** | Giriş veri olarak kullanılacak bayt sayısı. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Karma algoritması. Giriş veri için [DSA](../) imzasını döndürür. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) yöntemi

Belirtilen ikili akışın hash değerini belirtilen hash algoritmasıyla hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | İkili akış. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Karma algoritması. Giriş veri için [DSA](../) imzasını döndürür. |

## İlgili

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Sınıf [DSA](../)
* Yapı [HashAlgorithmName](../../hashalgorithmname/)
* AdAlanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)