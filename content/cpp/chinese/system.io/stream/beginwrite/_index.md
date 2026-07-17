---
title: BeginWrite()
second_title: Aspose.Slides for C++ API 参考
description: 发起一次异步写入操作。
type: docs
weight: 170
url: /zh/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) 方法


发起一次异步写入操作。

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含待写入数据的缓冲区 |
| offset | int | **buffer** 中的 0 基偏移，指示写入数据开始的位置 |
| count | int | 要写入的字节数 |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | 操作完成时要调用的回调 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步写入操作 |

### 返回值

表示已发起的异步写入操作的 [IAsyncResult](../../../system/iasyncresult/) 对象

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Object](../../../system/object/)
* 类 [Stream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)