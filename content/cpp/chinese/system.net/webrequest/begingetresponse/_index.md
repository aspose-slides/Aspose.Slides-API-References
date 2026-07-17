---
title: BeginGetResponse()
second_title: Aspose.Slides for C++ API 参考
description: 为资源发起异步请求。
type: docs
weight: 274
url: /zh/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) 方法


为资源发起异步请求。

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步操作。 |

### 返回值

一个[IAsyncResult](../../../system/iasyncresult/)对象，表示已发起的异步操作。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Object](../../../system/object/)
* 类 [WebRequest](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)