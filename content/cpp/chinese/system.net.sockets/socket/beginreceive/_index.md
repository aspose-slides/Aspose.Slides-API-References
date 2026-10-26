---
title: BeginReceive()
second_title: Aspose.Slides C++ API 参考
description: 发起异步写入操作。
type: docs
weight: 521
url: /zh/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) 方法

发起异步写操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用于接收数据的缓冲区。 |
| offset | **int32_t** | 指定数组中以字节为单位的偏移量。 |
| size | **int32_t** | 从‘offset’参数开始的指定数组中的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作完成时将被调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步接收操作。 |

### 返回值

表示已发起的异步接收操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## 另见

* 枚举 [SocketFlags](../../socketflags/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Object](../../../system/object/)
* 类 [Socket](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)