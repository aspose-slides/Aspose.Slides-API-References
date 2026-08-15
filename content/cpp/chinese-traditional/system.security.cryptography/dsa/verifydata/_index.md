---
title: VerifyData()
second_title: Aspose.Slides for C++ API 參考
description: 驗證指定資料的簽章是否有效。
type: docs
weight: 92
url: /zh-hant/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

驗證指定資料的簽章是否有效。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已簽署的資料。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。若簽章有效則回傳 true，否則回傳 false。 |

## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

驗證指定資料的簽章是否有效。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已簽署的資料。 |
| offset | **int32_t** | **data** 中的偏移位置。 |
| count | **int32_t** | 要雜湊的位元組數。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。若簽章有效則回傳 true，否則回傳 false。 |

## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

驗證指定二進位串流的簽章是否有效。

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 已簽署的資料。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽章資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。若簽章有效則回傳 true，否則回傳 false。 |

## 另請參閱

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* 類別 [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* 命名空間 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)