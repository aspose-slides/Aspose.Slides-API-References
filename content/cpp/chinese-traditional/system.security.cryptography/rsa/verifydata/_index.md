---
title: VerifyData()
second_title: Aspose.Slides for C++ API 參考
description: 驗證指定資料的簽章是否有效。
type: docs
weight: 157
url: /zh-hant/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) 方法

驗證指定資料的簽章是否有效。

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已簽署的資料。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | 填充模式。 如果簽章有效則回傳 true，否則回傳 false。 |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) 方法

驗證指定資料的簽章是否有效。

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已簽署的資料。 |
| offset | **int32_t** | data 的偏移量。 |
| count | **int32_t** | 要雜湊的位元組數。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | 填充模式。 如果簽章有效則回傳 true，否則回傳 false。 |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) 方法

驗證指定二進位串流的簽章是否有效。

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 已簽署的資料。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | 填充模式。 如果簽章有效則回傳 true，否則回傳 false。 |

## 另請參閱

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)