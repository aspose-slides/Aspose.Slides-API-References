---
title: SignData()
second_title: Aspose.Slides for C++ API 參考
description: 計算使用指定雜湊演算法的指定資料陣列的雜湊值，並對結果進行簽名。
type: docs
weight: 79
url: /zh-hant/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method

計算指定資料陣列的雜湊值（使用指定的雜湊演算法），並對結果進行簽名。

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 輸入資料陣列。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。返回 [DSA](../) 簽章以供輸入資料。 |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method

計算指定資料陣列的雜湊值（使用指定的雜湊演算法），並對結果進行簽名。

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 輸入資料陣列。 |
| offset | **int32_t** | **data** 的偏移量。 |
| count | **int32_t** | 作為輸入資料使用的位元組數。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。返回 [DSA](../) 簽章以供輸入資料。 |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) method

計算指定二進位串流的雜湊值（使用指定的雜湊演算法），並對結果進行簽名。

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 二進位串流。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。返回 [DSA](../) 簽章以供輸入資料。 |

## 參見

* 類型別名 [ByteArrayPtr](../../../system/bytearrayptr/)
* 類型別名 [StreamPtr](../../../system/streamptr/)
* 類別 [DSA](../)
* 結構 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)