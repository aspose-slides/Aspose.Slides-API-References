---
title: SignData()
second_title: Aspose.Slides for C++ API 參考
description: 計算指定輸入值的簽章。
type: docs
weight: 183
url: /zh-hant/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) method

計算指定輸入值的簽名。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) 用於讀取輸入資料。 |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 用於的雜湊演算法。 |

### 回傳值

[RSA](../../rsa/) 簽名，針對指定的資料。

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) method

計算指定輸入值的簽名。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 用於讀取被簽名資料的串流。 |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 用於的雜湊演算法。 |

### 回傳值

[RSA](../../rsa/) 簽名，針對指定的資料。

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) method

計算指定輸入值的簽名。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) 用於讀取輸入資料。 |
| offset | **int32_t** | 輸入緩衝區切片的起始索引。 |
| count | **int32_t** | 輸入緩衝區切片的大小。 |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 用於的雜湊演算法。 |

### 回傳值

[RSA](../../rsa/) 簽名，針對指定的資料。

## 另見

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)