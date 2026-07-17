---
title: BeginGetResponse()
second_title: Aspose.Slides C++ API 参考
description: 发起对资源的异步请求。
type: docs
weight: 170
url: /zh/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) 方法

发起对资源的异步请求。

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时将被调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步操作。 |

### 返回值

[IAsyncResult](../../../system/iasyncresult/) 对象，表示已启动的异步操作。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Object](../../../system/object/)
* 类 [FileWebRequest](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)