---
title: Read()
second_title: Aspose.Slides for C++ API 參考文件
description: 從串流讀取資料。
type: docs
weight: 14
url: /zh-hant/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

從串流讀取資料。

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 目標資料緩衝區。 |
| offset | **int32_t** | 目標緩衝區中的偏移量。 |
| count | **int32_t** | 要讀取的位元組數。 |

### 傳回值

實際讀取的位元組數。

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

從串流讀取資料。

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 目標資料緩衝區。 |
| offset | **int32_t** | 目標緩衝區中的偏移量。 |
| count | **int32_t** | 要讀取的位元組數。 |

### 傳回值

實際讀取的位元組數。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [CryptoStream](../)
* 命名空間 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)