---
title: WebProxy()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新实例。
type: docs
weight: 131
url: /zh/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() 构造函数

构造一个新实例。

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) 构造函数

构造一个新实例。

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 代理服务器地址。 |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) 构造函数

构造一个新实例。

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 代理服务器地址。 |
| BypassOnLocal | **bool** | 指示是否对本地地址使用代理服务器的值。 |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) 构造函数

构造一个新实例。

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 代理服务器地址。 |
| BypassOnLocal | **bool** | 指示是否对本地地址使用代理服务器的值。 |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | 不使用代理服务器的地址列表。 |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) 构造函数

构造一个新实例。

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 代理服务器地址。 |
| BypassOnLocal | **bool** | 指示是否对本地地址使用代理服务器的值。 |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | 不使用代理服务器的地址列表。 |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | 发送到代理服务器进行身份验证的凭据。 |

## WebProxy::WebProxy(String, int32_t) 构造函数

构造一个新实例。

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| Host | [String](../../../system/string/) | 主机名。 |
| Port | **int32_t** | 端口号。 |

## WebProxy::WebProxy(String) 构造函数

构造一个新实例。

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | 代理服务器地址。 |

## WebProxy::WebProxy(String, bool) 构造函数

构造一个新实例。

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | 代理服务器地址。 |
| BypassOnLocal | **bool** | 指示是否对本地地址使用代理服务器的值。 |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) 构造函数

构造一个新实例。

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | 代理服务器地址。 |
| BypassOnLocal | **bool** | 指示是否对本地地址使用代理服务器的值。 |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | 不使用代理服务器的地址列表。 |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) 构造函数

构造一个新实例。

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | 代理服务器地址。 |
| BypassOnLocal | **bool** | 指示是否对本地地址使用代理服务器的值。 |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | 不使用代理服务器的地址列表。 |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | 发送到代理服务器进行身份验证的凭据。 |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)