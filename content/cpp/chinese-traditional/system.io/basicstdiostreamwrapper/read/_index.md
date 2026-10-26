---
title: Read()
second_title: Aspose.Slides for C++ API 參考
description: 如果封裝模式是二進位，則從串流中讀取指定數量的位元組，否則讀取指定數量的字元並將其轉換為 uint8_t 類型。將讀取結果寫入指定的位元組陣列。
type: docs
weight: 66
url: /zh-hant/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

如果封裝模式是二進位，則從串流中讀取指定數量的位元組，否則讀取指定數量的字元並將其轉換為 **uint8_t** 類型。將讀取結果寫入指定的位元組陣列。

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 寫入已讀位元組的位元組陣列 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起點的寫入位置 |
| count | **int32_t** | 要讀取的位元組數 |

### 返回值

已讀取的位元組或字元數

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

從串流中讀取指定數量的位元組，並將其寫入指定的位元組陣列。

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 寫入已讀位元組的位元組視圖 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起點的寫入位置 |
| count | **int32_t** | 要讀取的位元組數 |

### 返回值

已讀取的位元組數

## 另請參閱

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [BasicSTDIOStreamWrapper](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)