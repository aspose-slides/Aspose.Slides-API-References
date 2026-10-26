---
title: SignData()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen veri dizisinin hash değerini hesaplar ve sonucu imzalar.
type: docs
weight: 131
url: /tr/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) metodu

Belirtilen veri dizisinin hash değerini hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Girdi veri dizisi. return ECDSA signature for the input data. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) metodu

Belirtilen veri dizisinin hash değerini hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Girdi veri dizisi. |
| offset | **int32_t** | **data** içinde ofset. |
| count | **int32_t** | Girdi verisi olarak kullanılacak bayt sayısı. return ECDSA signature for the input data. |

## ECDsaBotan::SignData(const StreamPtr\&) metodu

Belirtilen ikili akışın hash değerini hesaplar ve sonucu imzalar.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | İkili akış. return ECDSA signature for the input data. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metodu

Belirtilen veri dizisinin hash değerini, belirtilen hash algoritmasıyla hesaplar ve sonucu imzalar.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Girdi veri dizisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. return ECDSA signature for the input data. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metodu

Belirtilen veri dizisinin hash değerini, belirtilen hash algoritmasıyla hesaplar ve sonucu imzalar.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Girdi veri dizisi. |
| offset | **int32_t** | **data** içinde ofset. |
| count | **int32_t** | Girdi verisi olarak kullanılacak bayt sayısı. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. return ECDSA signature for the input data. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) metodu

Belirtilen ikili akışın hash değerini, belirtilen hash algoritmasıyla hesaplar ve sonucu imzalar.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | İkili akış. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. return ECDSA signature for the input data. |

## İlgili

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Sınıf [ECDsaBotan](../)
* Yapı [HashAlgorithmName](../../hashalgorithmname/)
* Ad alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)