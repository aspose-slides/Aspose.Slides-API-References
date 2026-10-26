---
title: CopyTo()
second_title: Aspose.Slides for C++ API 參考
description: 將位元組複製到指定的串流。
type: docs
weight: 209
url: /zh-hant/system.io/stream/copyto/
---
## Stream::CopyTo(const SharedPtr\<Stream\>\&) method


將位元組複製到指定的串流。

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | [Stream](../)，資料將被複製到此。 |

## Stream::CopyTo(const SharedPtr\<Stream\>\&, int32_t) method


將位元組複製到指定的串流，使用指定的緩衝區大小。

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination, int32_t buffer_size)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | [Stream](../)，資料將被複製到此。 |
| buffer_size | **int32_t** | 緩衝區的大小。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../)
* 命名空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)