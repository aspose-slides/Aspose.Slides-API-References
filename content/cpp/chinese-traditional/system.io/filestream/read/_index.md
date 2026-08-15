---
title: Read()
second_title: Aspose.Slides for C++ API 參考
description: 從串流中讀取指定數量的位元組，並寫入指定的位元組陣列。
type: docs
weight: 183
url: /zh-hant/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法


從串流中讀取指定數量的位元組，並寫入指定的位元組陣列。

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用於寫入已讀取位元組的位元組陣列。 |
| offset | **int32_t** | 在 **buffer** 中以 0 為基礎開始寫入的位址。 |
| count | **int32_t** | 要讀取的位元組數量。 |

### 返回值

已讀取的位元組數量。

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法


從串流中讀取指定數量的位元組，並寫入指定的位元組陣列。

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 用於寫入已讀取位元組的位元組陣列檢視。 |
| offset | **int32_t** | 在 **buffer** 中以 0 為基礎開始寫入的位址。 |
| count | **int32_t** | 要讀取的位元組數量。 |

### 返回值

已讀取的位元組數量。

## 另見

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [FileStream](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)