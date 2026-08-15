---
title: SignData()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的雜湊演算法計算指定資料陣列的雜湊值，並對結果進行簽章。
type: docs
weight: 79
url: /zh-hant/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method


計算指定資料陣列使用指定雜湊演算法的雜湊值，並對結果簽章。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 輸入資料陣列。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。傳回輸入資料的 ECDSA 簽章。 |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method


計算指定資料陣列使用指定雜湊演算法的雜湊值，並對結果簽章。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 輸入資料陣列。 |
| offset | **int32_t** | 在 **data** 中的偏移量。 |
| count | **int32_t** | 作為輸入資料的位元組數。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。傳回輸入資料的 ECDSA 簽章。 |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) method


計算指定二進位串流使用指定雜湊演算法的雜湊值，並對結果簽章。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 二進位串流。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。傳回輸入資料的 ECDSA 簽章。 |

## 另請參閱

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* 類別 [ECDsa](../)
* 結構 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)