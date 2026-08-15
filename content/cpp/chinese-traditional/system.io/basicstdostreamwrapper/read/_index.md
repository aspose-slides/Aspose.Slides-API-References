---
title: Read()
second_title: Aspose.Slides for C++ API 參考
description: 如果封裝模式為二進位，從串流讀取指定數量的位元組；否則讀取指定數量的字元並轉換為 uint8_t 類型。將讀取結果寫入指定的位元組陣列。不支援！
type: docs
weight: 66
url: /zh-hant/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

如果封裝模式是二進位，從串流讀取指定數量的位元組；否則讀取指定數量的字元並轉換為 **uint8_t** 類型。將讀取結果寫入指定的位元組陣列。不支援！

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用於寫入讀取位元組的位元組陣列 |
| offset | **int32_t** | 在 **buffer** 中開始寫入的零基位置 |
| count | **int32_t** | 要讀取的位元組數量 |

### 返回值

已讀取的位元組或字元數量

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

從串流讀取指定數量的位元組，並寫入指定的位元組陣列。

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 用於寫入讀取位元組的位元組視圖 |
| offset | **int32_t** | 在 **buffer** 中開始寫入的零基位置 |
| count | **int32_t** | 要讀取的位元組數量 |

### 返回值

已讀取的位元組數量

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [BasicSTDOStreamWrapper](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)