---
title: Read()
second_title: Aspose.Slides for C++ API 參考
description: 如果封裝模式為二進位，則從串流讀取指定的位元組數；否則讀取指定的字元數並將其轉換為 **uint8_t** 類型。將讀取結果寫入指定的位元組陣列。
type: docs
weight: 66
url: /zh-hant/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

如果包裝模式是二進位，則從串流讀取指定的位元組數；否則讀取指定的字元數並將其轉換為 **uint8_t** 類型。將讀取的結果寫入指定的位元組陣列。

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用於寫入讀取位元組的位元組陣列 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起點的寫入位置 |
| count | **int32_t** | 欲讀取的位元組數量 |

### 傳回值

傳回讀取的位元組或字元數

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

從串流讀取指定的位元組數，並將其寫入指定的位元組陣列。

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 用於寫入讀取位元組的位元組陣列檢視 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起點的寫入位置 |
| count | **int32_t** | 欲讀取的位元組數量 |

### 傳回值

傳回讀取的位元組數

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)