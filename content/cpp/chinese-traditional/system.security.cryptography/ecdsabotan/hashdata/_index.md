---
title: HashData()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的雜湊演算法計算指定資料陣列的雜湊值。
type: docs
weight: 105
url: /zh-hant/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) 方法

計算指定資料陣列使用指定雜湊演算法的雜湊值。

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) 要雜湊的。 |
| offset | **int32_t** | 在 **data** 中的偏移。 |
| count | **int32_t** | 要雜湊的位元組數。 |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | 雜湊演算法。 |

### 返回值

雜湊後的資料。

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) 方法

計算指定二進位串流使用指定雜湊演算法的雜湊值。

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | 要雜湊的二進位串流。 |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | 雜湊演算法。 |

### 返回值

雜湊後的資料。

## 另請參閱

* 型別別名 [ByteArrayPtr](../../../system/bytearrayptr/)
* 型別別名 [StreamPtr](../../../system/streamptr/)
* 類別 [ECDsaBotan](../)
* 結構 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空間 [System::Security::Cryptography](../../)
* 程式庫 [Aspose.Slides](../../../)