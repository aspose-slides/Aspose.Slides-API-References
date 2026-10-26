---
title: SignData()
second_title: Aspose.Slides for C++ API 參考文件
description: 計算指定資料陣列的雜湊值，並對結果簽章。
type: docs
weight: 131
url: /zh-hant/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) 方法

計算指定資料陣列的雜湊值，並對結果簽章。

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 輸入資料陣列。返回輸入資料的 ECDSA 簽章。 |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) 方法

計算指定資料陣列的雜湊值，並對結果簽章。

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 輸入資料陣列。 |
| offset | **int32_t** | 在 **data** 中的偏移。 |
| count | **int32_t** | 作為輸入資料的位元組數。返回輸入資料的 ECDSA 簽章。 |

## ECDsaBotan::SignData(const StreamPtr\&) 方法

計算指定二進位串流的雜湊值，並對結果簽章。

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 二進位串流。返回輸入資料的 ECDSA 簽章。 |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) 方法

使用指定的雜湊演算法計算指定資料陣列的雜湊值，並對結果簽章。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 輸入資料陣列。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。返回輸入資料的 ECDSA 簽章。 |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) 方法

使用指定的雜湊演算法計算指定資料陣列的雜湊值，並對結果簽章。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 輸入資料陣列。 |
| offset | **int32_t** | 在 **data** 中的偏移。 |
| count | **int32_t** | 作為輸入資料的位元組數。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。返回輸入資料的 ECDSA 簽章。 |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) 方法

使用指定的雜湊演算法計算指定二進位串流的雜湊值，並對結果簽章。

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 二進位串流。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。返回輸入資料的 ECDSA 簽章。 |

## 另請參閱

* 類型別名 [ByteArrayPtr](../../../system/bytearrayptr/)
* 類型別名 [StreamPtr](../../../system/streamptr/)
* 類別 [ECDsaBotan](../)
* 結構 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)