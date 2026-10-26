---
title: VerifyData()
second_title: Aspose.Slides for C++ API 參考
description: 驗證指定資料的簽名是否有效。
type: docs
weight: 170
url: /zh-hant/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) 方法

驗證指定資料的簽名是否有效。

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已簽署的資料。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽名資料。 如果簽名有效則回傳 true，否則 - false。 |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) 方法

驗證指定資料的簽名是否有效。

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已簽署的資料。 |
| offset | **int32_t** | 在 **data** 中的偏移。 |
| count | **int32_t** | 要雜湊的位元組數。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽名資料。 如果簽名有效則回傳 true，否則 - false。 |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) 方法

驗證指定二進位串流的簽名是否有效。

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 已簽署的資料。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽名資料。 如果簽名有效則回傳 true，否則 - false。 |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

驗證指定資料的簽名是否有效。

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已簽署的資料。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽名資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。 如果簽名有效則回傳 true，否則 - false。 |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

驗證指定資料的簽名是否有效。

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已簽署的資料。 |
| offset | **int32_t** | 在 **data** 中的偏移。 |
| count | **int32_t** | 要雜湊的位元組數。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽名資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。 如果簽名有效則回傳 true，否則 - false。 |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

驗證指定二進位串流的簽名是否有效。

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 已簽署的資料。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 簽名資料。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。 如果簽名有效則回傳 true，否則 - false。 |

## 參見

* 型別別名 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型別別名 [StreamPtr](../../../system/streamptr/)
* 類別 [ECDsaBotan](../)
* 結構 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)