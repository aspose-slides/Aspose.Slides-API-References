---
title: BeginRead()
second_title: Aspose.Slides for C++ API 参考
description: 发起一个异步读取操作。
type: docs
weight: 248
url: /zh/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

发起一个异步读取操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 读取的字节将写入的字节数组。 |
| offset | **int32_t** | 指定数组中以字节为单位的偏移量。 |
| size | **int32_t** | 要读取的字节数。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作完成时调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步读取操作。 |

### 返回值

一个表示已发起的异步读取操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Object](../../../system/object/)
* 类 [NetworkStream](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)