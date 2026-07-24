---
title: HashData()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen veri dizisinin karma değerini belirtilen karma algoritması kullanarak hesaplar.
type: docs
weight: 105
url: /tr/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) metod

Belirtilen veri dizisinin karma değerini belirtilen karma algoritması kullanarak hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) için karma. |
| offset | **int32_t** | **data** içindeki ofset. |
| count | **int32_t** | Karma için bayt sayısı. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Karma algoritması. |

### Döndürülen Değer

Karma yapılmış veri.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) metod

Belirtilen ikili akışın karma değerini belirtilen karma algoritması kullanarak hesaplar.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Karma yapılacak ikili akış. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Karma algoritması. |

### Döndürülen Değer

Karma yapılmış veri.

## Ayrıca Bakınız

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Sınıf [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Ad Alanı [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)