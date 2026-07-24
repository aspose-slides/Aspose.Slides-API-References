---
title: VerifyData()
second_title: Aspose.Slides for C++ API Referansı
description: Veri imzasını kontrol eder.
type: docs
weight: 209
url: /tr/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) metot

Veri imzasını kontrol eder.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) imzayı kontrol etmek için. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Alınan imza. |

### Dönüş Değeri

İmza geçerli ise true, aksi takdirde false.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metot

Belirtilen verinin imzasının geçerli olduğunu doğrular.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmzalanmış veri. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmza verisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Karma algoritması. İmza geçerli ise true, aksi takdirde false. |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metot

Belirtilen verinin imzasının geçerli olduğunu doğrular.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmzalanmış veri. |
| offset | **int32_t** | Verideki offset. |
| count | **int32_t** | Hashlenecek bayt sayısı. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmza verisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Karma algoritması. İmza geçerli ise true, aksi takdirde false. |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metot

Belirtilen ikili akışın imzasının geçerli olduğunu doğrular.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | İmzalanmış veri. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmza verisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Karma algoritması. İmza geçerli ise true, aksi takdirde false. |

## İlgili

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSACryptoServiceProvider](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)