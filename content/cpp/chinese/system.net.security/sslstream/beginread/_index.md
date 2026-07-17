---
title: BeginRead()
second_title: Aspose.Slides for C++ API 参考
description: 发起一次异步读取操作。
type: docs
weight: 417
url: /zh/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法


发起一次异步读取操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用于读取数据的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| count | **int32_t** | 要读取的字节数。 |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | 操作完成时调用的回调函数。 |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步读取操作。 |

### 返回值

一个表示已发起的异步读取操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Object](../../../system/object/)
* 类 [SslStream](../)
* 命名空间 [System::Net::Security](../../)
* 库 [Aspose.Slides](../../../)