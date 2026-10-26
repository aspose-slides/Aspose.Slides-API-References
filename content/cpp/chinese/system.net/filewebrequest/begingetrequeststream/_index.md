---
title: BeginGetRequestStream()
second_title: Aspose.Slides C++ API 参考
description: 启动一个异步操作，以获取用于向资源写入数据的流。
type: docs
weight: 144
url: /zh/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) 方法

启动一个异步操作，以获取用于向资源写入数据的流。

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 在操作完成时要调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步操作。 |

### 返回值

一个表示已启动的异步操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Object](../../../system/object/)
* 类 [FileWebRequest](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)