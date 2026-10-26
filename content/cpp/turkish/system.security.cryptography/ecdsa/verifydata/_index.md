---
title: VerifyData()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen verinin imzasının geçerli olduğunu doğrular.
type: docs
weight: 105
url: /tr/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metodu

Belirtilen verinin imzasının geçerli olduğunu doğrular.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmzalanmış veri. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmza verisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. İmza geçerli ise true, aksi takdirde false döndürür. |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metodu

Belirtilen verinin imzasının geçerli olduğunu doğrular.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmzalanmış veri. |
| offset | **int32_t** | Verideki ofset. |
| count | **int32_t** | Hashlenecek bayt sayısı. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmza verisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. İmza geçerli ise true, aksi takdirde false döndürür. |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metodu

Belirtilen ikili akışın imzasının geçerli olduğunu doğrular.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | İmzalanmış veri. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmza verisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. İmza geçerli ise true, aksi takdirde false döndürür. |

## Ayrıca Bakınız

* Tip Tanımı [ByteArrayPtr](../../../system/bytearrayptr/)
* Tip Tanımı [StreamPtr](../../../system/streamptr/)
* Sınıf [ECDsa](../)
* Yapı [HashAlgorithmName](../../hashalgorithmname/)
* İsim Alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)