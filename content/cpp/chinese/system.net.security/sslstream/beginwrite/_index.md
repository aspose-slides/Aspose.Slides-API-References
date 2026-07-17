---
title: BeginWrite()
second_title: Aspose.Slides for C++ API 参考
description: 启动异步写入操作。
type: docs
weight: 443
url: /zh/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法


启动一个异步写入操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用于写入数据的字节数组。 |
| offset | **int32_t** | 指定数组中以字节为单位的偏移量。 |
| count | **int32_t** | 要写入的字节数。 |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | 操作完成时将被调用的回调函数。 |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步写入操作。 |

### 返回值

一个表示已发起的异步写入操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Object](../../../system/object/)
* 类 [SslStream](../)
* 命名空间 [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)