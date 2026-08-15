---
title: Read()
second_title: Aspose.Slides for C++ API 參考
description: 從串流中讀取指定數量的位元組，並將其寫入指定的位元組陣列。
type: docs
weight: 391
url: /zh-hant/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


從串流中讀取指定數量的位元組，並將其寫入指定的位元組陣列。

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 寫入讀取位元組的位元組陣列 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起始的寫入位置 |
| count | **int32_t** | 要讀取的位元組數量 |

### 傳回值

已讀取的位元組數量

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


從串流中讀取指定數量的位元組，並將其寫入指定的位元組陣列。

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 寫入讀取位元組的位元組陣列 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起始的寫入位置 |
| count | **int32_t** | 要讀取的位元組數量 |

### 傳回值

已讀取的位元組數量

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [SslStream](../)
* 命名空間 [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)