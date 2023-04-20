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

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The proxy server address. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The proxy server address. |
| BypassOnLocal | **bool** | A value that indicates if the proxy server must be used for local addresses. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) constructor


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

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) constructor


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

## WebProxy::WebProxy(String, int32_t) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Host | [String](../../../system/string/) | The host name. |
| Port | **int32_t** | The port number. |

## WebProxy::WebProxy(String) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | The proxy server address. |

## WebProxy::WebProxy(String, bool) constructor


Constructs a new instance.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | The proxy server address. |
| BypassOnLocal | **bool** | A value that indicates if the proxy server must be used for local addresses. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) constructor


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

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) constructor


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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)