---
title: EndGetResponse()
second_title: Aspose.Slides 的 C++ API 参考
description: 等待对资源的指定异步请求完成。
type: docs
weight: 183
url: /zh/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) 方法

等待对资源的指定异步请求完成。

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 一个 [IAsyncResult](../../../system/iasyncresult/) 对象，表示对资源的异步请求。 |

### 返回值

Web 响应。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [WebResponse](../../webresponse/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [FileWebRequest](../)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)