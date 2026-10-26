---
title: HttpRequestMessage()
second_title: Aspose.Slides C++ API 参考
description: 构造一个新实例。
type: docs
weight: 131
url: /zh/system.net.http/httprequestmessage/httprequestmessage/
---
## HttpRequestMessage::HttpRequestMessage() 构造函数

构造一个新实例。

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage()
```

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, System::SharedPtr\<Uri\>) 构造函数

构造一个新实例。

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, System::SharedPtr<Uri> requestUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | HTTP 方法。 |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 请求资源的 URI。 |

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, String) 构造函数

构造一个新实例。

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, String requestUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | HTTP 方法。 |
| requestUri | [String](../../../system/string/) | 请求资源的 URI。 |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [HttpRequestMessage](../)
* 类 [HttpMethod](../../httpmethod/)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Net::Http](../../)
* 库 [Aspose.Slides](../../../)