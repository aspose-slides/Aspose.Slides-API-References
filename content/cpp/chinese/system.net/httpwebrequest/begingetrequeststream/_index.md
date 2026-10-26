---
title: BeginGetRequestStream()
second_title: Aspose.Slides C++ API 参考
description: 发起异步操作以获取用于向资源写入数据的流。
type: docs
weight: 469
url: /zh/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) 方法

发起异步操作以获取用于向资源写入数据的流。

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作完成时将被调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步操作。 |

### 返回值

表示已发起的异步操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Object](../../../system/object/)
* 类 [HttpWebRequest](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)