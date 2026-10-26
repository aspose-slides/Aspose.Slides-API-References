---
title: Write()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的位元組陣列寫入至串流。
type: docs
weight: 404
url: /zh-hant/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) 方法

將指定的位元組陣列寫入至串流。

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要寫入的位元組陣列。 |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

將指定位元組陣列中指定的子區段寫入至串流。

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要寫入位元組的陣列 |
| offset | **int32_t** | **buffer** 中子區段寫入起始元素的零基索引 |
| count | **int32_t** | 子區段中要寫入的元素數量 |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) 方法

將指定的位元組陣列寫入至串流。

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 要寫入的位元組陣列。 |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

將指定位元組陣列中指定的子區段寫入至串流。

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要寫入位元組的陣列 |
| offset | **int32_t** | **buffer** 中子區段寫入起始元素的零基索引 |
| count | **int32_t** | 子區段中要寫入的元素數量 |

## 參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)