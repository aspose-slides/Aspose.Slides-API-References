---
title: Details_WebException()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance.
type: docs
weight: 40
url: /cpp/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() constructor


Constructs a new instance.

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) constructor


Constructs a new instance.

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | The error description. |

## Details_WebException::Details_WebException(String, Exception) constructor


Constructs a new instance.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | The exception message. |
| innerException | [Exception](../../../system/exception/) | The inner exception. |

## Details_WebException::Details_WebException(String, WebExceptionStatus) constructor


Constructs a new instance.

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | The exception message. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | The status code. |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) constructor


Constructs a new instance.

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| message | [String](../../../system/string/) | The exception message. |
| innerException | [Exception](../../../system/exception/) | The inner exception. |
| status | [WebExceptionStatus](../../webexceptionstatus/) | The status code. |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | The web response with which the current exception is associated. |

## See Also

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Details_WebException](../)
* Class [String](../../../system/string/)
* Class [WebResponse](../../webresponse/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)