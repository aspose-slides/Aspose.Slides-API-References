---
title: VerifyData()
second_title: Aspose.Slides for C++ API 參考
description: 驗證指定資料的簽章是否有效。
type: docs
weight: 105
url: /zh-hant/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

驗證指定資料的簽章是否有效。

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已簽名的資料。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。若簽章有效則回傳 true，否則回傳 false。 |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

驗證指定資料的簽章是否有效。

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已簽名的資料。 |
| offset | **int32_t** | **data** 中的偏移量。 |
| count | **int32_t** | 要雜湊的位元組數量。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。若簽章有效則回傳 true，否則回傳 false。 |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

驗證指定二進位串流的簽章是否有效。

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 已簽名的資料。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。若簽章有效則回傳 true，否則回傳 false。 |

## 參見

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsa](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)