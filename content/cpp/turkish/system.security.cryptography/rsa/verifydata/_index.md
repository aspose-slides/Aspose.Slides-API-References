---
title: VerifyData()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen verinin imzasının geçerli olduğunu doğrular.
type: docs
weight: 157
url: /tr/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metot

Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmzalanmış veri. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmza verisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Dolgu modu. geçerli ise true döndürür, aksi takdirde false. |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metot

Verifies that the signature of the specified data is valid.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmzalanmış veri. |
| offset | **int32_t** | **data** içinde ofset. |
| count | **int32_t** | Hashlenecek bayt sayısı. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmza verisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Dolgu modu. geçerli ise true döndürür, aksi takdirde false. |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metot

Verifies that the signature of the specified binary stream is valid.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | İmzalanmış veri. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | İmza verisi. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Hash algoritması. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Dolgu modu. geçerli ise true döndürür, aksi takdirde false. |

## İlgili

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Sınıf [RSASignaturePadding](../../rsasignaturepadding/)
* Sınıf [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* İsimAlanı [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)