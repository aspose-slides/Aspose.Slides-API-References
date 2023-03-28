---
title: WebProxy()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance.
type: docs
weight: 131
url: /cpp/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy()
```

## See Also

* Class [WebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
## WebProxy::WebProxy([System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The proxy server address. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [WebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
## WebProxy::WebProxy([System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>, **bool**) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The proxy server address. |
| BypassOnLocal | **bool** | A value that indicates if the proxy server must be used for local addresses. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [WebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
## WebProxy::WebProxy([System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>, **bool**, [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The proxy server address. |
| BypassOnLocal | **bool** | A value that indicates if the proxy server must be used for local addresses. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | The list of addresses that do not use the proxy server. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [WebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
## WebProxy::WebProxy([System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>, **bool**, [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>, [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\>) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The proxy server address. |
| BypassOnLocal | **bool** | A value that indicates if the proxy server must be used for local addresses. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | The list of addresses that do not use the proxy server. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | The credentials that are sent to the proxy server for authentication. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Class [WebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
## WebProxy::WebProxy([String](../../../system/string/), **int32_t**) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Host | [String](../../../system/string/) | The host name. |
| Port | **int32_t** | The port number. |

## See Also

* Class [String](../../../system/string/)
* Class [WebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
## WebProxy::WebProxy([String](../../../system/string/)) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | The proxy server address. |

## See Also

* Class [String](../../../system/string/)
* Class [WebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
## WebProxy::WebProxy([String](../../../system/string/), **bool**) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | The proxy server address. |
| BypassOnLocal | **bool** | A value that indicates if the proxy server must be used for local addresses. |

## See Also

* Class [String](../../../system/string/)
* Class [WebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
## WebProxy::WebProxy([String](../../../system/string/), **bool**, [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | The proxy server address. |
| BypassOnLocal | **bool** | A value that indicates if the proxy server must be used for local addresses. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | The list of addresses that do not use the proxy server. |

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
## WebProxy::WebProxy([String](../../../system/string/), **bool**, [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>, [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\>) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | The proxy server address. |
| BypassOnLocal | **bool** | A value that indicates if the proxy server must be used for local addresses. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | The list of addresses that do not use the proxy server. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | The credentials that are sent to the proxy server for authentication. |

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICredentials](../../icredentials/)
* Class [WebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
