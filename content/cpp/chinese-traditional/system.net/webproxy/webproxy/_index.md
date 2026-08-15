---
title: WebProxy()
second_title: Aspose.Slides C++ API 參考
description: 建立新的實例。
type: docs
weight: 131
url: /zh-hant/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() 建構函式


建立新的實例。

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) 建構函式


建立新的實例。

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 代理伺服器位址。 |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) 建構函式


建立新的實例。

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 代理伺服器位址。 |
| BypassOnLocal | **bool** | 指示是否對本機位址使用代理伺服器的值。 |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) 建構函式


建立新的實例。

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 代理伺服器位址。 |
| BypassOnLocal | **bool** | 指示是否對本機位址使用代理伺服器的值。 |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | 不使用代理伺服器的位址清單。 |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) 建構函式


建立新的實例。

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 代理伺服器位址。 |
| BypassOnLocal | **bool** | 指示是否對本機位址使用代理伺服器的值。 |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | 不使用代理伺服器的位址清單。 |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | 用於向代理伺服器驗證的憑證。 |

## WebProxy::WebProxy(String, int32_t) 建構函式


建立新的實例。

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| Host | [String](../../../system/string/) | 主機名稱。 |
| Port | **int32_t** | 埠號。 |

## WebProxy::WebProxy(String) 建構函式


建立新的實例。

```cpp
System::Net::WebProxy::WebProxy(String Address)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | 代理伺服器位址。 |

## WebProxy::WebProxy(String, bool) 建構函式


建立新的實例。

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | 代理伺服器位址。 |
| BypassOnLocal | **bool** | 指示是否對本機位址使用代理伺服器的值。 |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) 建構函式


建立新的實例。

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | 代理伺服器位址。 |
| BypassOnLocal | **bool** | 指示是否對本機位址使用代理伺服器的值。 |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | 不使用代理伺服器的位址清單。 |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) 建構函式


建立新的實例。

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| Address | [String](../../../system/string/) | 代理伺服器位址。 |
| BypassOnLocal | **bool** | 指示是否對本機位址使用代理伺服器的值。 |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | 不使用代理伺服器的位址清單。 |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | 用於向代理伺服器驗證的憑證。 |

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [WebProxy](../)
* 類別 [Uri](../../../system/uri/)
* 類別 [String](../../../system/string/)
* 類別 [ICredentials](../../icredentials/)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)