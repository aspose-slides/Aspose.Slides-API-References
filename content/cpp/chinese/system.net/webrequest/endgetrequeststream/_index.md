---
title: EndGetRequestStream()
second_title: Aspose.Slides 的 C++ API 参考
description: 等待指定的获取流的异步操作完成。
type: docs
weight: 313
url: /zh/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) 方法

等待指定的获取流的异步操作完成。

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) 对象，表示获取流的异步操作。 |

### 返回值

用于向资源写入数据的流。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../../system.io/stream/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [WebRequest](../)
* 命名空间 [System::Net](../../)
* Library [Aspose.Slides](../../../)