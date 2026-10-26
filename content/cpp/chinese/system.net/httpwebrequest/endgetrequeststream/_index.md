---
title: EndGetRequestStream()
second_title: Aspose.Slides for C++ API 参考
description: 等待指定的获取流的异步操作完成。
type: docs
weight: 482
url: /zh/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) 方法

等待指定的获取流的异步操作完成。

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 一个 [IAsyncResult](../../../system/iasyncresult/) 对象，表示获取流的异步操作。 |

### 返回值

用于向资源写入数据的流。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../../system.io/stream/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [HttpWebRequest](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)