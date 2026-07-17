---
title: BeginWrite()
second_title: Aspose.Slides C++ API 参考
description: 发起一个异步写操作。
type: docs
weight: 274
url: /zh/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

发起一个异步写操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含待写入数据的缓冲区。 |
| offset | **int32_t** | 指定数组中以字节为单位的偏移量。 |
| size | **int32_t** | 要写入的字节数。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作完成时调用的回调函数。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步写操作。 |

### 返回值

一个 [IAsyncResult](../../../system/iasyncresult/) 对象，表示已发起的异步写操作。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Object](../../../system/object/)
* 类 [NetworkStream](../)
* 命名空间 [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)