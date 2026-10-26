---
title: HttpClient()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新实例。
type: docs
weight: 92
url: /zh/system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() 构造函数


构造一个新实例。

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) 构造函数


构造一个新实例。

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | 用于发送请求的 HTTP 处理程序。 |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) 构造函数


构造一个新实例。

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | 用于发送请求的 HTTP 处理程序。 |
| disposeHandler | **bool** | 指示在释放此实例时是否必须释放处理程序的值。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [HttpClient](../)
* 类 [HttpMessageHandler](../../httpmessagehandler/)
* 命名空间 [System::Net::Http](../../)
* 库 [Aspose.Slides](../../../)