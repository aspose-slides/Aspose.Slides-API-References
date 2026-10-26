---
title: VerifyData()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查資料簽章。
type: docs
weight: 209
url: /zh-hant/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) 方法

檢查資料簽章。

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) 用於檢查簽章。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 接收到的簽章。 |

### Return Value

True if signature is valid, false otherwise.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

驗證指定資料的簽章是否有效。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已簽署的資料。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。若簽章有效則傳回 true，否則傳回 false。 |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

驗證指定資料的簽章是否有效。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已簽署的資料。 |
| offset | **int32_t** | 在 **data** 中的偏移量。 |
| count | **int32_t** | 要雜湊的位元組數。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。若簽章有效則傳回 true，否則傳回 false。 |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

驗證指定二進位串流的簽章是否有效。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 已簽署的資料。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。若簽章有效則傳回 true，否則傳回 false。 |

## 另請參閱

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSACryptoServiceProvider](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)