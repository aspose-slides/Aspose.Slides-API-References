---
title: Details_WebException()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新实例。
type: docs
weight: 40
url: /zh/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() 构造函数

构造一个新实例。

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) 构造函数

构造一个新实例。

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 错误描述。 |

## Details_WebException::Details_WebException(String, Exception) 构造函数

构造一个新实例。

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 异常消息。 |
| innerException | [Exception](../../../system/exception/) | 内部异常。 |

## Details_WebException::Details_WebException(String, WebExceptionStatus) 构造函数

构造一个新实例。

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 异常消息。 |
| status | [WebExceptionStatus](../../webexceptionstatus/) | 状态码。 |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) 构造函数

构造一个新实例。

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 异常消息。 |
| innerException | [Exception](../../../system/exception/) | 内部异常。 |
| status | [WebExceptionStatus](../../webexceptionstatus/) | 状态码。 |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | 当前异常关联的 Web 响应。 |

## 另请参阅

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Details_WebException](../)
* 类 [String](../../../system/string/)
* 类 [WebResponse](../../webresponse/)
* 命名空间 [System::Net](../../)
* Library [Aspose.Slides](../../../)