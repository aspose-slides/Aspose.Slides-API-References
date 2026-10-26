---
title: SignData()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的雜湊演算法和填充模式計算指定資料陣列的雜湊值，並對結果進行簽名。
type: docs
weight: 131
url: /zh-hant/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) 方法

計算指定資料陣列使用指定雜湊演算法和填充模式的雜湊值，並對結果簽名。

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 輸入資料陣列。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | 填充模式。返回 [RSA](../) 簽章，用於輸入資料。 |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) 方法

計算指定資料陣列使用指定雜湊演算法和填充模式的雜湊值，並對結果簽名。

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 輸入資料陣列。 |
| offset | **int32_t** | 在 **data** 中的偏移量。 |
| count | **int32_t** | 作為輸入資料使用的位元組數。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | 填充模式。返回 [RSA](../) 簽章，用於輸入資料。 |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) 方法

計算指定二進位串流使用指定雜湊演算法和填充模式的雜湊值，並對結果簽名。

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 二進位串流。 |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 雜湊演算法。 |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | 填充模式。返回 [RSA](../) 簽章，用於輸入資料。 |

## 另請參閱

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* 類別 [RSASignaturePadding](../../rsasignaturepadding/)
* 類別 [RSA](../)
* 結構 [HashAlgorithmName](../../hashalgorithmname/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)